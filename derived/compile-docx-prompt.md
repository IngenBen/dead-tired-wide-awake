# Prompt: Compile Sleep Inc. manuscript to .docx

Use this prompt verbatim in a new session to regenerate `sleep_inc_manuscript.docx` from scratch.

---

Compile all 26 chapters from `/book/` into a single print-ready Word document (`sleep_inc_manuscript.docx`) and save it to the workspace folder.

## Critical constraints

**OneDrive truncation.** The `/book/` folder is cloud-synced via OneDrive. Many files are only partially cached on disk — bash and Python `open()` will silently read a truncated version. The Read tool downloads the full cloud file. You must read every chapter via the Read tool, then write the complete content to `outputs/book/` (a local sandbox directory), and run all preprocessing from there.

**Do not edit `/book/`.** It is read-only per CLAUDE.md.

**Keep all headings.** Chapter titles (`# Chapter N - Title`) and structural headers (PART, Phase) are part of the document — do not strip them.

## Step-by-step

### Step 1 — Read all chapters via the Read tool

Read each of the 26 chapter files from the workspace folder `/book/` using the Read tool (not bash). The chapters are named:

```
ch01 - The Weight of It.md
ch02 - The Turning Point.md
ch03 - The Uncomfortable Truth.md
ch04 - Sleep Incorporated.md
ch05 - Adenosine.md
ch06 - Melatonin.md
ch07 - Cortisol.md
ch08 - Dopamine.md
ch09 - What Goes Wrong.md
ch10 - Taking Ownership.md
ch11 - Your Feedback Loop.md
ch12 - Supplements.md
ch13 - Your Sleep Environment.md
ch14 - Habit 1 - Caffeine.md
ch15 - Habit 2 - Alcohol.md
ch16 - Habit 3 - Food Timing.md
ch17 - Habit 4 - Can't sleep routine.md
ch18 - Habit 5 - Your Morning Routine.md
ch19 - Habit 6 - Your Evening Routine.md
ch20 - Habit 7 - Meditation.md
ch21 - Habit 8 - Napping.md
ch22 - Habit 9 - Exercise.md
ch23 - Habit 10 - Social Media.md
ch24 - Habit 11 - Hydration & waking up to pee.md
ch25 - Habit 12 - Sugar & Food Sensitivities.md
ch26 - What Happens Next.md
```

You can batch these in parallel Read calls. Once read, write each file's complete content to `/outputs/book/<filename>` using the Write tool. Do not use bash to copy them — bash reads the truncated disk version.

### Step 2 — Create the preprocessing script via bash heredoc

Write the following script to `/outputs/preprocess.py` using a bash heredoc (not the Write tool — the Write tool has a truncation bug with longer scripts):

```bash
cat > /sessions/.../mnt/outputs/preprocess.py << 'PYEOF'
#!/usr/bin/env python3
import re, os

BOOK_DIR   = "/sessions/.../mnt/Sleep Incorporated/book/"
LOCAL_DIR  = "/sessions/.../mnt/outputs/book/"
ASSETS_DIRS = [
    "/sessions/.../mnt/Sleep Incorporated/assets/images/",
    "/sessions/.../mnt/Sleep Incorporated/assets/Graphs/",
]
OUTPUT_MD  = "/sessions/.../mnt/outputs/combined.md"

CHAPTERS = [
    "ch01 - The Weight of It.md",
    "ch02 - The Turning Point.md",
    "ch03 - The Uncomfortable Truth.md",
    "ch04 - Sleep Incorporated.md",
    "ch05 - Adenosine.md",
    "ch06 - Melatonin.md",
    "ch07 - Cortisol.md",
    "ch08 - Dopamine.md",
    "ch09 - What Goes Wrong.md",
    "ch10 - Taking Ownership.md",
    "ch11 - Your Feedback Loop.md",
    "ch12 - Supplements.md",
    "ch13 - Your Sleep Environment.md",
    "ch14 - Habit 1 - Caffeine.md",
    "ch15 - Habit 2 - Alcohol.md",
    "ch16 - Habit 3 - Food Timing.md",
    "ch17 - Habit 4 - Can't sleep routine.md",
    "ch18 - Habit 5 - Your Morning Routine.md",
    "ch19 - Habit 6 - Your Evening Routine.md",
    "ch20 - Habit 7 - Meditation.md",
    "ch21 - Habit 8 - Napping.md",
    "ch22 - Habit 9 - Exercise.md",
    "ch23 - Habit 10 - Social Media.md",
    "ch24 - Habit 11 - Hydration & waking up to pee.md",
    "ch25 - Habit 12 - Sugar & Food Sensitivities.md",
    "ch26 - What Happens Next.md",
]

PAGE_BREAK = ''

def find_image(filename):
    for assets_dir in ASSETS_DIRS:
        direct = os.path.join(assets_dir, filename)
        if os.path.exists(direct): return direct
        for f in os.listdir(assets_dir):
            if f.lower() == filename.lower():
                return os.path.join(assets_dir, f)
    return None

def convert_obsidian_image(line):
    m = re.match(r'^\s*!\[\[([^\]|]+?)(?:\|(\d+))?\]\]\s*$', line)
    if not m: return None
    filename = m.group(1).strip()
    px_width = m.group(2)
    if re.search(r'graph\s*[-]', filename, re.IGNORECASE):
        return '\n*[Graph not yet available]*\n'
    img_path = find_image(filename)
    if not img_path:
        return '\n*[Image: ' + filename + ']*\n'
    if px_width:
        w = int(px_width) / 96.0
        return '\n![' + filename + '](' + img_path + '){width=%.1fin}\n' % w
    return '\n![' + filename + '](' + img_path + '){width=4.5in}\n'

def process_chapter(raw):
    lines = raw.split('\n')
    out = []
    for line in lines:
        if line.strip() == 'GRAPH': continue
        # Replace standalone --- with * * * to prevent pandoc's yaml_metadata_block
        # extension from treating --- ... --- spans as YAML and dropping chapters.
        # Root cause: ch04 ends with --- before footnotes; ch10 ends with ---; pandoc
        # swallows everything between them (ch05–ch10) as a failed YAML block.
        if re.match(r'^-{3,}\s*$', line):
            out.append('* * *'); continue
        if '![[' in line:
            replacement = convert_obsidian_image(line)
            if replacement is not None:
                out.append(replacement); continue
            def inline_replace(m):
                fname = m.group(1).strip(); px = m.group(2)
                path = find_image(fname)
                if not path: return '*[Image: ' + fname + ']*'
                if px:
                    w = int(px) / 96.0
                    return '![' + fname + '](' + path + '){width=%.1fin}' % w
                return '![' + fname + '](' + path + '){width=4.5in}'
            line = re.sub(r'!\[\[([^\]|]+?)(?:\|(\d+))?\]\]', inline_replace, line)
        out.append(line)
    return '\n'.join(out).strip()

parts = []
for idx, fname in enumerate(CHAPTERS):
    local_path = os.path.join(LOCAL_DIR, fname)
    fpath = local_path if os.path.exists(local_path) else os.path.join(BOOK_DIR, fname)
    source = 'LOCAL' if os.path.exists(local_path) else 'disk '
    with open(fpath, 'r', encoding='utf-8') as fh:
        raw = fh.read()
    processed = process_chapter(raw)
    if not processed:
        print('WARNING: empty ' + fname); continue
    print('[%s] %d lines  %s' % (source, len(raw.split('\n')), fname))
    if idx > 0: parts.append(PAGE_BREAK)
    parts.append(processed)

combined = '\n\n'.join(parts)
with open(OUTPUT_MD, 'w', encoding='utf-8') as fh:
    fh.write(combined)
print('Done: %d chapters, %d chars' % (len(CHAPTERS), len(combined)))
PYEOF
```

Replace the `...` path segments with the actual session path from your system prompt. Run it with `python3 /sessions/.../mnt/outputs/preprocess.py`.

**Verify:** every chapter should show `[LOCAL]` in the output (not `[disk ]`). If any show `[disk ]`, that chapter wasn't written to outputs/book/ and will likely be truncated.

### Step 3 — Create reference.docx

Run this Python script via bash to create the pandoc reference document:

```python
from docx import Document
from docx.shared import Pt, Inches, RGBColor
from docx.enum.text import WD_LINE_SPACING

OUT = "/sessions/.../mnt/outputs/reference.docx"
doc = Document()
section = doc.sections[0]
section.page_width   = Inches(8.27)   # A4
section.page_height  = Inches(11.69)  # A4
section.left_margin  = Inches(0.5)    # narrow
section.right_margin = Inches(0.5)    # narrow
section.top_margin   = Inches(0.5)    # narrow
section.bottom_margin = Inches(0.5)   # narrow

BLACK = RGBColor(0, 0, 0)

def set_style(style, font_name, size_pt, bold=False,
              space_before=0, space_after=10, line_spacing=1.2):
    f = style.font
    f.name = font_name; f.size = Pt(size_pt); f.bold = bold
    try: f.color.rgb = BLACK
    except: pass
    pf = style.paragraph_format
    pf.space_before = Pt(space_before); pf.space_after = Pt(space_after)
    pf.line_spacing_rule = WD_LINE_SPACING.MULTIPLE
    pf.line_spacing = line_spacing

# Body text: Aptos 10pt
set_style(doc.styles['Normal'], 'Aptos', 10, space_before=0, space_after=8, line_spacing=1.3)

# Heading 1 – chapter titles and Part/Phase headers
h1 = doc.styles['Heading 1']
set_style(h1, 'Aptos', 18, bold=True, space_before=28, space_after=12, line_spacing=1.1)
h1.paragraph_format.page_break_before = False  # no page breaks between chapters

# Heading 2 – sub-section headings (##)
set_style(doc.styles['Heading 2'], 'Aptos', 13, bold=True,
          space_before=18, space_after=8, line_spacing=1.1)

doc.save(OUT)
print('reference.docx written')
```

### Step 4 — Run pandoc

```bash
pandoc /sessions/.../mnt/outputs/combined.md \
  --from=markdown+implicit_figures \
  --to=docx \
  --reference-doc=/sessions/.../mnt/outputs/reference.docx \
  -o /sessions/.../mnt/outputs/sleep_inc_manuscript.docx
```

### Step 5 — Copy to workspace and present

```bash
cp /sessions/.../mnt/outputs/sleep_inc_manuscript.docx \
   "/sessions/.../mnt/Sleep Incorporated/sleep_inc_manuscript.docx"
```

Then call `present_files` with the workspace path so the user can open it.

## Known image references in the book

These images exist in `/assets/Graphs/` and will be embedded:
- `Adenosine.png` (ch05)
- `Melatonin.png` (ch06)
- `Cortisol.png` (ch07)
- `Dopamine.png` (ch08)
- `ExecutivesLineUp.png` (ch04 or ch09)
- `bad-sleep.jpeg`, `good-sleep.jpeg`

Any `![[graph - ...]]` references to graphs that don't exist as files are replaced with `*[Graph not yet available]*` by the preprocessing script.

## Typography spec

- Body text: **Aptos 10pt**, 1.3× line spacing, 8pt space after paragraph
- Heading 1 (chapter titles, Part/Phase headers): Aptos 18pt bold
- Heading 2 (## subheadings): Aptos 13pt bold
- Page: A4 (8.27" × 11.69"), narrow margins 0.5" all sides
- No page breaks between chapters (chapters flow continuously)
