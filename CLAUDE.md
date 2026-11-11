# Sleep Book — Wiki Schema (CLAUDE.md)

This file configures you (the LLM agent) as the maintainer of a wiki built from a
finished book manuscript. It is based on Andrej Karpathy's "LLM Wiki" pattern, with
one deliberate inversion described below. Read this file at the start of every session.

## Purpose

This vault decomposes a ~30,000-word, ~26-chapter book about sleep into a structured,
interlinked wiki. The wiki does two jobs:

1. **Now — editorial audit.** Surface cross-chapter problems the author can't see while
   editing one chapter at a time: duplication, contradictions, inconsistent terminology,
   over-explaining, tone drift, and claims that lack support.
2. **Later — grounded knowledge base.** Once the book is final, answer questions, draft
   social posts and video outlines, and feed an app — all grounded in the book, with
   every point traceable back to a chapter.

## The one inversion that governs everything

In Karpathy's pattern, raw sources are feedstock and the wiki becomes the artifact you
rely on. **Here it is reversed.** The manuscript is the product and the source of truth.
The author's voice is the point. The wiki is a *derived* analysis layer that sits
underneath the book — never above it.

Therefore: **you never change text in `/book/` directly.** When I ask you to edit a
chapter, you mark up the changes in the chapter as CriticMarkup tracked changes, which I
accept or reject in Obsidian with Review Critic (see "Editing rules for /book/"). This single rule is what protects the author's voice and keeps
the manuscript authoritative.

## Layers and folders

- `/book/` — the manuscript, one file per chapter (`ch01.md` … `ch26.md`). **Source of
  truth. Edit only with tracked changes, and only when I ask.**
- `/assets/` — supporting source material for the book: data files, spreadsheets, graph
  data, images, and other non-prose inputs. Read-only to you; place files here manually.
- `/wiki/` — your output. One markdown page per concept, technique, claim, or recurring
  anecdote. You own this layer entirely.
- `/audit/` — your editorial findings and proposed edits. You own this.
- `/derived/` — (used later) query results worth keeping: FAQ answers, video outlines,
  app explainers. You own this.
- `index.md` — catalog of every wiki page.
- `log.md` — append-only timeline of operations.
- `CLAUDE.md` — this schema. We co-evolve it as we learn what works.

## Editing rules for /book/ (CriticMarkup)

Never change text in `/book/` directly. Every edit must be written as CriticMarkup so I
can accept or reject it in Obsidian:

- Additions: {++new text++}
- Deletions: {--removed text--}
- Replacements: {~~old text~>new text~~}

Rules:
- Keep my original wording intact inside the markup. Don't rewrite text outside it.
- Never put markup across table cells, heading markers (#), list bullets or code fences.
  Change the whole table row or line instead.
- Keep each change as small as possible: change words or phrases, not whole sentences or
  paragraphs. Only replace a whole sentence when most of it changes.
- Don't nest markup inside other markup.
- Don't remove or accept existing CriticMarkup. Only I do that.
- Don't add {>>comments<<} to explain your changes. Give the reason for each change in the
  chat instead, numbered in the order the changes appear in the note.
- When reading `/book/` for BUILD, AUDIT, QUERY or endnotes, treat pending markup as not
  yet accepted: read the original text.
- Before each editing pass, commit the current state in git. After I finish reviewing,
  check for stray markup and commit the result.

**On sources:** there are no external sources and no citations — the only input is the
book. So this is *decomposition*, not accumulation: a one-time BUILD pass across the 26
chapters, then ongoing AUDIT and (later) QUERY.

## File map — canonical vs working

- **`/derived/claims-knowledge-base.md`** — master claim registry with sourced evidence.
  Source of truth for all endnote content. Entries tagged `<!-- endnote -->` or
  `<!-- contested --> <!-- endnote -->` feed the Notes section in `/book/endnotes.md`.
  152 entries tagged (49 also contested; 2026-11-09: Ch8 note 'Can looking forward to something keep you awake?' added, +1; 2026-10-28: Ch6 'genuinely useful' note split into N2–N5, net +3. Originally counted by script 2026-10-19 after the KB sync, which rebuilt
  every tagged entry from the Notes wording plus the decided rewrites; old working headings kept as
  `<!-- was: … -->`; the short cross-reference notes are tagged entries with no sources, placed after
  the untagged entry that carries the substance). Compiled output is 152 notes
  (`audit/clean-2026-11-09/endnotes.md`, single current copy awaiting Ben's merge into /book/endnotes.md, together with the clean chapters in the same folder; change list in `audit/clean-2026-11-09/endnotes-changes.md`; earlier clean copies archived in `audit/archive/2026-10-28/` and `audit/archive/2026-11-09/`). Sources
  S001–S251 are saved in `/derived/sources/` (S192–S213 COLLECTED, pending decisions or merge; S214–S247 COLLECTED 2026-11-03/04 as background for the why-change-is-hard explainer, not cited in the book; S248–S250 COLLECTED 2026-11-09 for the new Ch8 excitement note; S251 COLLECTED 2026-11-09 for the Ch4 hormones note, pending merge) (catalogue.md, index.md); each source file ends with a
  written summary in the `derived/study-summary-template.md` format (added 2026-10-19, from the saved text only). Chapter numbers in the KB must match
  `/book/endnotes.md`.
- **`/book/endnotes.md`** — the reader-facing Notes section, now part of the manuscript.
  A subset of the KB in neutral encyclopedia voice. Edited with tracked changes like the
  rest of `/book/`.
  Rebuild from the KB, never from `endnotes-draft.md`.
- **`/audit/archive/2026-09-24/`** — holds the former `endnotes-final.md` (superseded by
  `/book/endnotes.md`) and `continuity-coherence-pass.md` (the full-manuscript continuity
  audit; historical reference only), archived 2026-09-24.
- **`/audit/archive/claim-references*.md`** — earlier source-research working files
  predating the KB; legacy reference only.
- **`/derived/explainers/`** — detailed reasoning behind chapter prose: how findings fit
  together, mechanisms, practical rules, and what is still reasoning rather than sourced. One
  living file per topic (no dates in names; update in place). The KB holds the atomic claims
  with sources (untagged unless they become endnotes) and points to the explainer; wiki pages
  link to it. First: `melatonin-dose-and-timing.md` (2026-10-21). Also `why-change-is-hard.md` (2026-11-03): background beyond the book (deeper view of the willpower thread); no KB entries, entries in summary-plus-sources format so they can be lifted into the KB if the book uses them.
- **`/derived/three-pillars-mapping.md`** — habit-to-pillar assignment and the current
  five-phase structure (Food Timing = Ch16, Habit 3; Phase 6 removed 2026-09-25).
- **`/audit/archive/`** — spent files: all `-proposed` edits (hand-applied by author),
  scratch-pads, `endnotes-draft.md`, superseded passes. Do not edit; do not treat as
  current.

## Wiki page format

Every wiki page is YAML frontmatter plus a short body.

```
---
title: Sleep pressure
aliases: [sleep drive, adenosine load]   # every other term the book uses for this
type: concept                            # concept | technique | claim | anecdote
level: core                              # theme | core | detail (keeps importance from going flat)
status: established-science              # established-science | original-idea | anecdote | unsure
appears_in:                              # INTERNAL CITATIONS — point into the book
  - ch02: mentioned in passing
  - ch07: defined properly
  - ch14: re-explained from scratch      # duplication signal
  - ch22: referenced
canonical: <the single definition / wording to standardise on>
---

One short paragraph of synthesis in neutral wiki voice.
[[Wikilinks]] to related pages.

notes: contradictions, drift, or anything the AUDIT should see.
```

**Do not copy the author's sentences into wiki pages.** Summarise in plain wiki voice.
The book holds the voice; the wiki holds the skeleton.

## Operations

### BUILD — decompose the book (replaces Karpathy's "ingest")

Work **one chapter per pass** unless told otherwise. For each chapter:

1. Read the chapter from `/book/`.
2. Extract its concepts, techniques, claims, and recurring anecdotes.
3. For each item, **search the existing wiki first.**
   - If a page already exists, **edit it**: add this chapter to `appears_in`, merge any
     new nuance, and add an alias if the book named the thing differently here.
   - Only **create** a new page when nothing matches.
   - (This search-first rule is how we avoid spawning duplicate pages for one idea.)
4. Add `[[wikilinks]]` between related pages.
5. Update `index.md`.
6. Append a `log.md` entry.

Surface what you found — duplications, oddities, contradictions — before moving to the
next chapter. Stay involved chapter by chapter; do not batch silently.

### AUDIT — the editorial payoff (replaces Karpathy's "lint")

On request, health-check the whole wiki and write findings to `/audit/`. Look for:

- **Duplication / over-explaining:** any concept whose `appears_in` lists 3+ chapters, or
  that is defined at length more than once. Propose which instance to keep and which to
  cut or replace with a cross-reference.
- **Contradictions:** pages where the book asserts X in one chapter and not-X in another.
- **Terminology drift:** `aliases` revealing the same thing was named differently across
  chapters. Propose one canonical term.
- **Tone / cadence drift:** flag chapters whose register noticeably diverges from the
  book's baseline (much warmer or colder, denser or looser).
- **Orphan techniques:** a technique referenced but never actually explained, or a claim
  the book leans on but never sets up.
- **Unsupported science:** any page with `status: established-science` and no support.
  List these — they are where a citation will be needed before the social/app phase.

Each finding = location (chapter), what's wrong, and a proposed fix. **Findings go to
`/audit/`. Don't mark up `/book/` from an audit unless I ask.**

### QUERY — later, for the social and app phase

Answer questions strictly from the wiki and the book, grounded, naming the chapter each
point came from. Good answers (a Facebook reply, a video outline, an app explainer) get
filed back as new pages under `/derived/` so they compound. Flag anything that would
assert beyond what the book actually supports.

### Content ideas backlog (`/derived/content-ideas.md`)

A forward-looking list of things to write about later (posts, videos, app explainers).
Ideas live here, **not** in `/wiki/` — wiki pages must trace to the book via `appears_in`,
and ideas have no chapter yet. Keep each idea grounded where possible (note the chapter or
`[[wiki page]]` it grows out of).

**When I ask to add an idea, prompt me for any required field I have not supplied before
writing it** — at minimum: format, angle/hook, grounded-in (chapter/wiki page), audience,
status. Ask once, concisely, then file it.

### REWORD — suggest a rewording in chat

When I say **"recommend changes"** or **"show me changes"**, suggest a rewording of the
passage currently under discussion and show it in the chat window (do not edit any file).

Display rules:

- Show the rewording as **plain rendered text** (not a code block), with amendments inline:
  **bold** for added wording, ~~strikethrough~~ for removed wording.
- Include context: show the previous paragraph, the amended paragraph, and the following
  paragraph.
- If the previous or following paragraph is 2 sentences or fewer, include one additional
  paragraph on that side.

This is a chat-only suggestion. If I then want it recorded, it is marked up in the chapter
as tracked changes (see "Editing rules for /book/").

### SUMMARY PLUS SOURCES — the house style for weak / contested evidence

When a claim has no clean-cut evidence (mixed, weak, or contested), the preferred resolution
is **accept the prose + add an endnote in this format**. When I say **"summary plus sources"**,
produce exactly this:

1. **A short, honest, plain-English summary in neutral encyclopedia voice** — usually 2–4
   sentences. It concedes what the evidence does *not* show as plainly as what it does,
   names the direction of the best studies in lay terms (e.g. "a typical dose did not change
   measured sleep"), and notes where the full chain has not been demonstrated end-to-end.
   No statistics, p-values, or effect sizes in the prose itself.
2. **The source(s)** beneath — author, year, journal, DOI/stable link, one per line. Hard
   numbers (effect sizes, CIs, sample sizes) and credibility caveats fold into a plain
   parenthetical on the source line, not into the summary prose.

Tone: clear, factual, measured — not academic hedging and not author confessional. The
worked reference example is the Ch3 note 'Is CBN really more sleep-targeted than CBD?' in
`derived/claims-knowledge-base.md`. Reuse
existing citations from the KB; only search again if asked to firm a source up.

### ENDNOTE PRESENTATION STYLE — the locked reader-facing format

The book uses **no in-text endnote markers** (no superscript numbers, no ⟦EN:…⟧ tokens in the
prose). Instead the back matter has a **Notes section grouped by chapter**, and the reader
finds a note by scanning headings, not by chasing a number.

Each note is rendered as:

- A **chapter group header** ("Chapter 18 — Breathe"), with notes inside it in **reading order**
  (top of chapter to bottom).
- A **bold identifying heading of ~5–8 words**, phrased as the *question the reader has*
  ("Does the 528 Hz frequency itself aid sleep?") — findable from memory of the passage.
- The **neutral-encyclopedia-voice summary** (where the note has one): factual, measured,
  conceding what the evidence does not show — not author confessional.
- The **source(s)** beneath, author–year–journal–DOI/stable link. No "Sources:" label and no
  asterisk/italic working-file formatting; any credibility caveat folds into a plain parenthetical.

Because the order is positional within each chapter (not a global running number), this section
can be compiled **without** waiting for pending tracked changes in `/book/` to be accepted.

Working vs. publishable split: `derived/claims-knowledge-base.md` is the working file (all
tagged entries are the endnote source of truth); `book/endnotes.md` is the compiled
reader-facing output (edited only with tracked changes). `endnotes-draft.md` is archived — do not use it.

## index.md

A catalog of every wiki page, grouped by type (techniques, concepts, claims, anecdotes),
each with its one-line summary and its `appears_in` chapters. Update it on every BUILD
pass. Read it first when answering a QUERY.

## log.md

Append-only. One entry per operation, with a consistent prefix so it stays greppable:

```
## [2026-05-31] build | ch07
## [2026-05-31] audit | duplication pass
## [2026-06-01] query | caffeine FAQ -> filed to /derived/
```

## Hard rules (do not violate)

1. Never change `/book/` text directly. Edits are CriticMarkup tracked changes, made only
   when I say which chapter and to go ahead.
2. Never copy the author's prose into the wiki. Summarise in wiki voice.
3. Search before you create — edit an existing page rather than spawning a duplicate.
4. Every claim records where in the book it appears (`appears_in`) and whether it is
   established science or the author's own idea (`status`).
5. Writeback: useful query results get filed as pages, not left in chat.
6. One chapter per BUILD pass; stay involved.
