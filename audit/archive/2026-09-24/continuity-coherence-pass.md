# Continuity & Coherence Pass — Full Manuscript (Ch 1–26)

**Date:** 2026-06-16 · **Revised:** 2026-06-16 (see Correction Notice) · **Updated:** 2026-06-30 (ch09 "What Goes Wrong" inserted; chapters 9–25 renumbered to 10–26)
**Scope:** All 26 chapters in `/book/`. Checked for voice inconsistencies, cross-chapter
contradictions, broken through-lines, and terminology drift.
**Status:** Proposals only. Per CLAUDE.md, `/book/` is read-only — every fix below is for the
author to apply by hand.

---

## ⚠ Correction Notice (read first)

The **first version of this log was wrong on its headline findings.** It reported that four
chapters (7, 18, 22, 24) "end mid-sentence" and that Ch 18 had an orphaned footnote. **None of
that is true.** All four chapters are complete, and the Ch 18 footnote text is present.

**What happened:** the first pass read the chapters through the Linux **shell mount**, which served
**stale, truncated copies** of those four OneDrive-synced files (e.g. it saw Ch 7 as 8,412 bytes
ending "…sent extra cort", while the live file continues "…sent extra **cortisol into the next
morning, making the whole cycle harder to break.** The signal was never the problem. The rhythm
was. Cortisol at least announces itself. The next one doesn't."). The shell did not error — it
returned valid-looking but incomplete text — so the cut-offs were mistaken for unfinished drafts.

**This revision** retracts those five findings (see *Retracted* below) and re-validates the
remainder against the file reader, which fetches the live OneDrive copy. The root-cause write-up
is in the chat reply that accompanied this revision.

### How to read the references
Paragraph numbers (`¶N`) count blank-line-separated blocks from the top of each chapter file,
including heading lines. Each citation also includes a short anchor quote.

### Revised severity at a glance

| # | Finding | Chapters | Severity |
|---|---------|----------|----------|
| T1 | Central "Sleep Incorporated / you're the CEO" metaphor never reprised in the close | 4, 9 → 25 | High |
| T2 | "I'll show you exactly what to expect, and when" promise only loosely paid off | 2 → 9 | Medium |
| T3 | "How the WHOOP came about — a story for later" set up but never closed as a callback | 2 → 10 | Low |
| X1 | Napping timing rule stated two different ways | 16 vs 19 | Medium |
| X2 | "Two stages you met in Chapter 11" — deep sleep first appears in Ch 5 | 14 vs 5 | Low |
| X3 | Duplicated closing block — same point stated twice, near-verbatim | 14 | Medium |
| V1 | Tone drift — coolest/most metric-dense register in the book | 10, 20 | Medium |
| V2 | Only markdown table in the manuscript (format outlier vs prose-list style) | 11 | Medium |
| V3 | Length/cadence drift — longest, most how-to-dense chapter | 18 | Low |
| D1 | "Habit N" label appears in only 2 of 12 habit-chapter headings; colon vs dash | 13, 24 vs 14–23 | Medium |
| D2 | Phase headings exist for Phases 1, 2, 4, 5 but not 3 or 6 | 16, 22 | Medium |
| D3 | No `# PART 1` heading (Parts 2–5 are labelled) | 1 | Low |
| D4 | Part 3 ("The Program") contains a single chapter | 9 | Low |
| D5 | Inconsistent capitalisation of "Executive(s)" | 7 + others | Low |
| ~~C1~~ | ~~Chapter ends mid-sentence~~ — **RETRACTED (tooling artifact, chapters are complete)** | 7, 18, 22, 24 | retracted |
| ~~C2~~ | ~~Orphaned footnote~~ — **RETRACTED (footnote present, Ch 18 line 128)** | 18 | retracted |

---

## Contradictions, duplication & cross-reference slips

No hard factual contradictions were found in the science — hormone timings, doses, half-life,
the 2 a.m. mechanism, the 10 p.m.-bed / ~6 a.m.-wake baseline, and the 4-hour/6-hour exercise
margins are all internally consistent across chapters. Three smaller issues are worth resolving.

### X1 — Napping timing stated two different ways (Ch 16 vs Ch 19)
- **Ch 16 ¶19:** *"the shortest nap you can manage. Twenty minutes at most. Not before mid-morning
  and not in the late afternoon."*
- **Ch 19 ¶7:** *"Keep it short — twenty minutes at most. Don't nap within eight hours of your
  bedtime."*

The 20-minute cap matches, but the timing windows use different reference frames. For a 10 p.m.
bedtime, "within eight hours of bedtime" rules out anything after ~2 p.m., whereas "not in the late
afternoon" reads as a later cut-off. **Proposed fix:** State one rule and cross-reference it (Ch 16
already gestures at Ch 19's method).

### X2 — "The two stages you met in Chapter 11" (Ch 14 ¶13)
Ch 14 ¶13 attributes deep sleep and REM to Chapter 11. REM is indeed introduced in Ch 10 (¶22),
but **deep sleep is first introduced in Ch 5** (¶12) and Ch 14 ¶15 itself re-cites deep-sleep
clearing as "Chapter 5." So one paragraph points readers to Ch 10 for a concept they met in Ch 5.
**Proposed fix:** "deep sleep (Chapter 5) and REM (Chapter 11)…", or "the two restorative stages
you've met."

### X3 — Duplicated closing block (Ch 14 ¶57–63) *(new in this revision)*
The end of the Alcohol chapter makes the same point twice in immediately consecutive blocks:
- **¶57–59:** *"…if you're not ready to change anything yet… do something, not nothing. Find the
  smallest possible move. One fewer drink. One night a week without. / Something that shifts the
  habit even slightly is worth more than a clean commitment you abandon in a fortnight. The
  direction matters more than the distance."*
- **¶61–63:** *"…if the idea of giving up the evening drink is overwhelming right now, still do
  something, not nothing. Find the smallest possible move. One fewer drink. One night a week
  without. / A small shift you hold onto is worth more than a big commitment you drop. The
  direction matters more than the distance."*

Both close on the identical line *"The direction matters more than the distance."* This reads like a
leftover draft duplicate. **Proposed fix:** Keep one version and cut the other.

---

## Broken / unclosed through-lines

### T1 — The "Sleep Incorporated / you're the CEO" metaphor is never reprised in the close
*(re-validated against the live Ch 25.)* This is the book's **title metaphor** and central frame:
- **Ch 4 ¶2:** *"think about the sleep system as a hierarchy, like a company… Sleep Incorporated.
  You're the CEO."*
- **Ch 4 ¶36:** *"You're the CEO of Sleep Incorporated. You've always owned it…"*
- **Ch 9** is titled **"Taking Ownership"** and opens (¶2): *"I was the CEO of Sleep Incorporated,
  which meant it was mine to fix."*

After Ch 9 the *executives* language continues, but the **CEO / you-own-the-company** frame is
dropped — and the final chapter closes on the **fitness** metaphor instead (Ch 25 ¶9, *"Nobody
tries to get fit on the night of a race"*; ending ¶37–39, *"The mind that wouldn't switch off can
learn to. Now go get some sleep."*) without returning the reader to the CEO's chair.
**Proposed fix:** Add a short reprise in Ch 25 — the company finally runs itself / the executives
aligned — to close the loop the title opens.

### T2 — "I'll show you exactly what to expect, and when" (Ch 2 ¶29)
What's delivered (Ch 9 ¶17) is a **rough** estimate — *"roughly a phase a week… through them in six
weeks… go slower and that's fine too"* — plus a qualitative "partway through you'll notice it." No
concrete "what to expect, when" timeline. **Proposed fix:** Soften the Ch 2 promise, or add the
expectation map it implies.

### T3 — The WHOOP "story for later" (Ch 2 ¶25)
Ch 2 ¶25 plants *"how that came about is a story for later."* The origin lands in Ch 10 (¶4, the
runner friend who posts him a tracker), but it's never tied back to the Ch 2 hook, and Ch 10 ¶4
doesn't name the device as the WHOOP at the moment of the call (named later, ¶29/¶34).
**Proposed fix:** A one-line callback in Ch 10 closes the loop.

---

## Voice & register inconsistencies

Baseline per `/derived/author-style-notes.md`: warm, plain, first-person, short paragraphs,
prose-style lists rather than bullets/tables, science kept brief. Voice is consistent across the
memoir and explainer chapters (1–9), and the personal-grounding standard is met in every explainer
chapter. The drift is concentrated in the data-heavy chapters.

### V1 — Coolest, most metric-dense register (Ch 10 and Ch 20)
Ch 10 ¶16–19 stack three one-line questions as a bulleted list and ¶30 quotes validation-study
figures; Ch 20 ¶15 runs through WHOOP strain/recovery mechanics in a near-manual register. Both
meet the personal-grounding bar, so the issue is register, not voice absence. **Proposed fix:**
Re-warm the transitions; let a personal line carry each block of metrics.

### V2 — The only table in the book (Ch 11 ¶13)
Ch 11 uses a markdown quick-reference table (Supplement / Form / Dosage) — the single table in the
manuscript, against a style baseline that favours prose lists. **Proposed fix:** Keep it
deliberately as the one reference exhibit, or render it as the author's usual stacked-prose list.

### V3 — Length/cadence drift (Ch 18)
Ch 18 is the longest chapter and the most how-to-dense (breath counts, 528 Hz audio, body position,
session timing, plus a footnote). Some heft is justified — the author ranks meditation first
(¶20) — but against a baseline that prizes plainness, it reads long. **Proposed fix:** Consider
splitting the "why it works" from the "how to do it," or trimming toward the author's shorter cadence.

---

## Terminology & structural-label drift

### D1 — "Habit N" label inconsistent across habit-chapter headings
The in-text H1 headings carry the habit number in only two chapters, which also disagree on
punctuation: **Ch 13 ¶1** `# Chapter 14 - Habit 1: Caffeine` and **Ch 24 ¶1**
`# Chapter 25 - Habit 12: Sugar & Food Sensitivities` (both colon), while **Ch 14–23** use plain
titles with no habit number. **Proposed fix:** Pick one convention and apply it to all twelve.

### D2 — Phase headings present for 1, 2, 4, 5 — but not 3 or 6
Explicit `# Phase N` headings appear for Phase 1 (Ch 10 ¶3), Phase 2 (Ch 13 ¶1), Phase 4 (Ch 18 ¶1)
and Phase 5 (Ch 20 ¶2). Phase 3 and Phase 6 are only mentioned inline ("Phase 3 begins in the
morning," Ch 15 ¶32 / "Phase 3 is now in place," Ch 17 ¶22 / "Hydration is the first chapter in
Phase 6," Ch 22 ¶2) — Ch 16 and Ch 22 open with no phase heading. **Proposed fix:** Add
`# Phase 3 – …` atop Ch 16 and `# Phase 6 – …` atop Ch 22.

### D3 — No `# PART 1` heading
`# PART 2` (end of Ch 2), `# PART 3` (end of Ch 8), `# PART 4` (top of Ch 10) and `# PART 5` (top of
Ch 25) are labelled, but the opening memoir chapters (1–2) have no `# PART 1`. **Proposed fix:** Add
one for symmetry, or confirm the open is intentionally unlabelled.

### D4 — Part 3 is a single chapter
`# PART 3 – The Program` (end of Ch 8) contains only Ch 9 before `# PART 4 – The habits` begins at
Ch 10. **Proposed fix:** Consider folding Ch 9 into the front of Part 4, or confirm it's deliberate.

### D5 — Capitalisation of "Executive(s)"
Usually capitalised ("Wake Executive(s)"), but slips occur — e.g. Ch 7 ¶23 *"the Cortisol
executive"* (lower-case). **Proposed fix:** Normalise (recommend capitalised as the named role).

---

## Retracted findings (were in the first version — now known false)

- **C1 — "Four chapters end mid-sentence" (Ch 7, 18, 22, 24): RETRACTED.** All four are complete in
  the live files. The first pass read truncated copies served by the shell mount. Verified endings:
  Ch 7 ends *"…Cortisol at least announces itself. The next one doesn't."*; Ch 18 ends *"…That's the
  muscle. Keep building it."* (+ footnote); Ch 22 ends *"…Just giving your body what it already
  expects."*; Ch 24 ends *"…Twenty-four chapters, twelve habits. The program is built."*
- **C2 — "Orphaned footnote in Ch 18": RETRACTED.** The footnote text is present (Ch 18 line 128:
  *"If you are a neuroscientist, you will know this is not exactly true — the relationship is
  bidirectional…"*).

---

## Notes for the author (not defects)
- Cross-references between chapters are **accurate** where checked (Ch 5's disruptor list → Chs
  12/13/14/16/17/18/21; Ch 8 → 15/17; Ch 21 → 8/15; Ch 18 → 7/15; Ch 20 → 2/16).
- The three-signal / three-job spine (activate / calm / timing → stop activation / build calming /
  train the clock) is mapped consistently across Ch 4 ¶5+¶38, Ch 9 ¶7, Ch 10 ¶2 and Ch 25 ¶6/¶11.
- The "fitness, not a switch" metaphor (Ch 3 ¶15–16) and the "I'll never be a good sleeper" story
  (Ch 2 ¶32 → Ch 9 ¶18 → Ch 25 ¶8/¶15) are both cleanly set up and paid off.

> **Methodology note:** This revision was validated against the file-reader copies (live OneDrive
> content). The shell mount is unreliable for this vault — it can return stale/truncated copies of
> cloud-synced files without erroring. Treat the file reader as the source of truth here.
