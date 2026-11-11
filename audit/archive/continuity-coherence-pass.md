# Continuity & Coherence Pass — Full Manuscript (Ch 1–25)

**Date:** 2026-06-16
**Scope:** All 25 chapters in `/book/`. Checked for voice inconsistencies, cross-chapter
contradictions, broken through-lines, and terminology drift.
**Status:** Proposals only. Per CLAUDE.md, `/book/` is read-only — every fix below is for the
author to apply by hand.
**Source:** All chapter text was read through the file reader (live OneDrive copy). The Linux shell
mount is unreliable for this vault — it can silently return stale/truncated copies of cloud-synced
files — so it was not used as a source for any finding here.

### How to read the references
`¶N` = the Nth non-empty block from the top of the chapter file (counting heading lines as blocks).
Each citation also carries a short anchor quote so the passage is findable even if blocks are
counted differently.

### Severity at a glance

| # | Finding | Chapters | Severity |
|---|---------|----------|----------|
| T1 | Central "Sleep Incorporated / you're the CEO" metaphor never reprised in the close | 4, 9 → 25 | High |
| T2 | "I'll show you exactly what to expect, and when" promise only loosely paid off | 2 → 9 | Medium |
| T3 | The WHOOP "story for later" is set up but never closed as a callback | 2 → 10 | Low |
| X1 | Napping timing rule stated two different ways | 16 vs 19 | Medium |
| X2 | "Two stages you met in Chapter 10" — but deep sleep first appears in Ch 5 | 14 vs 5 | Low |
| X3 | Duplicated closing block — the same point made twice, near-verbatim | 14 | Medium |
| V1 | Tone drift — coolest / most metric-dense register in the book | 10, 20 | Medium |
| V2 | The only markdown table in the manuscript (format outlier vs prose-list style) | 11 | Medium |
| V3 | Length / cadence drift — longest, most how-to-dense chapter | 18 | Low |
| D1 | "Habit N" label appears in only 2 of 12 habit-chapter headings; colon vs dash | 13, 24 vs 14–23 | Medium |
| D2 | Phase headings exist for Phases 1, 2, 4, 5 but not 3 or 6 | 16, 22 | Medium |
| D3 | No `# PART 1` heading (Parts 2–5 are labelled) | 1–2 | Low |
| D4 | Part 3 ("The Program") contains a single chapter | 9 | Low |
| D5 | Inconsistent capitalisation of "Executive(s)" | 7 + others | Low |

---

## Broken / unclosed through-lines

### T1 — The "Sleep Incorporated / you're the CEO" metaphor is never reprised in the close
This is the book's **title metaphor** and its central organising frame:
- **Ch 4 ¶2:** *"think about the sleep system as a hierarchy, like a company… Sleep Incorporated.
  You're the CEO."*
- **Ch 4 ¶36:** *"You're the CEO of Sleep Incorporated. You've always owned it…"*
- **Ch 9** is titled **"Taking Ownership"** and opens (¶2): *"I was the CEO of Sleep Incorporated,
  which meant it was mine to fix."*

After Ch 9 the *executives* language continues throughout the habit chapters, but the explicit
**CEO / you-own-the-company** frame is dropped — and the final chapter closes on the **fitness**
metaphor instead (Ch 25 ¶5, *"Nobody tries to get fit on the night of a race"*; ending ¶20, *"The
mind that wouldn't switch off can learn to. Now go get some sleep."*) without returning the reader
to the CEO's chair. A title-level frame the reader is told they "own" deserves a closing callback.
**Proposed fix:** Add a short reprise in Ch 25 — the company now runs itself / the executives
finally aligned — to close the loop the title opens.

### T2 — "I'll show you exactly what to expect, and when" (Ch 2 ¶29)
Ch 2 ¶29 promises: *"I'll show you exactly what to expect, and when, before you begin."* What's
delivered (Ch 9 ¶17) is a **rough** estimate — *"roughly a phase a week… through them in six weeks…
go slower and that's fine too"* — plus the qualitative "somewhere partway through you'll notice it."
There's no concrete "what to expect, when" timeline. **Proposed fix:** Either soften the Ch 2
promise ("I'll give you a sense of what to expect, and roughly when") or add the expectation map the
stronger wording implies.

### T3 — The WHOOP "story for later" (Ch 2 ¶25)
Ch 2 ¶25 plants a hook: *"My WHOOP was tracking through all of it, too — though how that came about
is a story for later."* The origin is delivered in Ch 10 (¶4, the runner friend who posts him a
tracker), but it's never tied back to the Ch 2 promise, and Ch 10 ¶4 doesn't name the device as the
WHOOP at the moment of the call (it's named later, ¶29/¶34). **Proposed fix:** A one-line callback
in Ch 10 ("this was the WHOOP I mentioned earlier") closes the loop the reader was told to wait for.

---

## Contradictions, duplication & cross-reference slips

No hard factual contradictions were found in the science — hormone timings, doses, half-life, the
2 a.m. mechanism, the 10 p.m.-bed / ~6 a.m.-wake baseline, and the 4-hour/6-hour exercise margins
are all internally consistent across chapters. Three smaller issues are worth resolving.

### X1 — Napping timing stated two different ways (Ch 16 vs Ch 19)
- **Ch 16 ¶19:** *"the shortest nap you can manage. Twenty minutes at most. Not before mid-morning
  and not in the late afternoon."*
- **Ch 19 ¶7:** *"Keep it short — twenty minutes at most. Don't nap within eight hours of your
  bedtime."*

The 20-minute cap matches, but the timing windows use different reference frames. For a 10 p.m.
bedtime, "within eight hours of bedtime" rules out anything after ~2 p.m., whereas "not in the late
afternoon" reads as a later cut-off. A reader comparing the two could be unsure where the line is.
**Proposed fix:** State one rule and cross-reference it (Ch 16 already gestures at Ch 19's method).

### X2 — "The two stages you met in Chapter 10" (Ch 14 ¶13)
Ch 14 ¶13 attributes deep sleep and REM to Chapter 10. REM is indeed introduced in Ch 10 (¶22),
but **deep sleep is first introduced in Ch 5** (¶12, *"During sleep, particularly deep (slow wave)
sleep, the brain clears adenosine"*), and Ch 14 itself re-cites deep-sleep clearing as "Chapter 5"
two paragraphs later. So one sentence points the reader to Ch 10 for a concept they first met in
Ch 5. **Proposed fix:** "deep sleep (Chapter 5) and REM (Chapter 10)…", or "the two restorative
stages you've met."

### X3 — Duplicated closing block (Ch 14 ¶29–32)
The end of the Alcohol chapter makes the same point twice in immediately consecutive blocks:
- **¶29–30:** *"And if you're not ready to change anything yet… do something, not nothing. Find the
  smallest possible move. One fewer drink. One night a week without. / Something that shifts the
  habit even slightly is worth more than a clean commitment you abandon in a fortnight. The
  direction matters more than the distance."*
- **¶31–32:** *"And if the idea of giving up the evening drink is overwhelming right now, still do
  something, not nothing. Find the smallest possible move. One fewer drink. One night a week
  without. / A small shift you hold onto is worth more than a big commitment you drop. The direction
  matters more than the distance."*

Both blocks close on the identical line *"The direction matters more than the distance."* This reads
like a leftover draft duplicate. **Proposed fix:** Keep one version and cut the other.

---

## Voice & register inconsistencies

Baseline per `/derived/author-style-notes.md`: warm, plain, first-person, short paragraphs,
prose-style lists rather than bullets/tables, science kept brief and immediately translated. Voice
is consistent across the memoir and explainer chapters (1–9), and the personal-grounding standard
is met in every explainer chapter. The drift that exists is concentrated in the data-heavy chapters.

### V1 — Coolest, most metric-dense register (Ch 10 and Ch 20)
- **Ch 10 (Feedback Loop) ¶16–19** stack three one-line questions as a bulleted-style list, and
  **¶30** quotes validation-study figures (*"around twenty to thirty minutes, narrowing to roughly
  ten…"*). It's the most clinical stretch in the book.
- **Ch 20 (Exercise) ¶15** runs through WHOOP strain/recovery mechanics (*"WHOOP tracks both strain
  and recovery…"*) in a register closer to a product manual than the surrounding memoir voice.

Both chapters *do* meet the personal-grounding bar (the friend's tracker call in Ch 10; the
mountain-biking thread in Ch 20), so the issue is register, not voice absence. **Proposed fix:**
Re-warm the openings/transitions and let one personal line carry each block of metrics, so the data
sits inside the author's voice rather than replacing it.

### V2 — The only table in the book (Ch 11 ¶13)
Ch 11 uses a markdown quick-reference **table** (Supplement / Form / Dosage). The style notes
explicitly flag tables/bullets as a departure from the author's intentional prose-list style, and
it's the single table in the manuscript, so it stands out as a format outlier. **Proposed fix:**
Either keep it deliberately as the one reference exhibit (and note that choice), or render the three
supplements as the author's usual stacked-prose list.

### V3 — Length / cadence drift (Ch 18, Meditation)
Ch 18 is by far the longest chapter and the most how-to-dense (breath counts, 528 Hz audio, body
position, session timing, plus a footnote). Some heft is justified — the author ranks meditation
first (¶20, *"Meditation would take first place instantly"*) — but against a baseline that prizes
plainness, it reads long. **Proposed fix:** Consider splitting the "why it works" (biology) from the
"how to do it" (protocol), or trimming the protocol detail toward the author's shorter cadence.

---

## Terminology & structural-label drift

### D1 — "Habit N" label inconsistent across habit-chapter headings
Filenames label habits 1–12 (ch13–ch24), but the **in-text H1 headings** carry the habit number in
only two chapters, which also disagree on punctuation:
- **Ch 13:** `# Chapter 13 - Habit 1: Caffeine` (colon)
- **Ch 24:** `# Chapter 24 - Habit 12: Sugar & Food Sensitivities` (colon)
- **Ch 14–23:** plain titles with **no** habit number (e.g. `# Chapter 14 - Alcohol`,
  `# Chapter 16 - Your Morning Routine`).

So 10 of the 12 habit chapters drop the "Habit N" label the reader is primed to follow.
**Proposed fix:** Pick one heading convention and apply it to all twelve.

### D2 — Phase headings present for 1, 2, 4, 5 — but not 3 or 6
Explicit `# Phase N` headings appear for **Phase 1** (top of Ch 10), **Phase 2** (top of Ch 13),
**Phase 4** (top of Ch 18) and **Phase 5** (top of Ch 20). But **Phase 3** and **Phase 6** are only
mentioned inline, never given a heading:
- Phase 3 — only "Phase 3 begins in the morning" (end of Ch 15) and "Phase 3 is now in place"
  (Ch 17 ¶22). Ch 16, where Phase 3 starts, opens with no phase heading.
- Phase 6 — only "Hydration is the first chapter in Phase 6" inline (Ch 22 ¶2).

**Proposed fix:** Add `# Phase 3 – …` atop Ch 16 and `# Phase 6 – …` atop Ch 22 to match the others.

### D3 — No `# PART 1` heading
`# PART 2 – The Science` (end of Ch 2), `# PART 3 – The Program` (end of Ch 8),
`# PART 4 – The habits` (top of Ch 10) and `# PART 5 – Over to you` (top of Ch 25) are all labelled,
but there is no `# PART 1` heading for the opening memoir chapters (1–2). **Proposed fix:** Add a
`# PART 1 – …` heading for symmetry, or confirm the open is intentionally unlabelled.

### D4 — Part 3 is a single chapter
`# PART 3 – The Program` (declared at the end of Ch 8) contains only Ch 9 before
`# PART 4 – The habits` begins at Ch 10. A one-chapter part sits oddly beside the multi-chapter
Parts 2 and 4. **Proposed fix:** Consider folding Ch 9 into the front of Part 4, or confirm the
single-chapter part is deliberate.

### D5 — Capitalisation of "Executive(s)"
The cast is usually capitalised ("Wake Executive(s)", "Sleep Executives"), but casing slips in
places — e.g. **Ch 7 ¶23** *"When the Cortisol executive refuses to pack up…"* (lower-case
"executive"). **Proposed fix:** Normalise to one style (recommend capitalised when used as the
named role).

---

## Notes for the author (not defects)
- The four chapters that are still in active drafting (7, 18, 22, 24) are **complete and end
  cleanly** in the live files — e.g. Ch 7 closes *"Cortisol at least announces itself. The next one
  doesn't."* and Ch 24 closes *"Twenty-four chapters, twelve habits. The program is built."*
- Cross-references between chapters are **accurate** where checked (Ch 5's disruptor list → Chs
  12/13/14/16/17/18/21; Ch 8 → 15/17; Ch 21 → 8/15; Ch 18 → 7/15; Ch 20 → 2/16).
- The three-signal / three-job spine (activate / calm / timing → stop activation / build calming /
  train the clock) is mapped consistently across Ch 4 ¶5+¶38, Ch 9 ¶7, Ch 10 ¶2 and Ch 25 ¶6.
- The "fitness, not a switch" metaphor (Ch 3 ¶15–16) and the "I'll never be a good sleeper" story
  (Ch 2 ¶32 → Ch 9 ¶18 → Ch 25 ¶8) are both cleanly set up and paid off.
