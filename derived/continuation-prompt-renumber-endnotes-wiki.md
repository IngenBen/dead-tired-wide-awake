# Continuation prompt: renumber endnotes and wiki after the Food Timing move

*Written 2026-09-25. Paste everything below the line into a new session.*

---

Read `CLAUDE.md` first and follow it. `/book/` is read-only, so any change to `book/endnotes.md` must be delivered as a clean copy in `/audit/` for me to merge by hand. `/wiki/`, `/derived/` and `index.md` belong to you, so edit those directly. Append a `log.md` entry for each operation.

## What already happened (book side: done and verified 2026-09-25)

Food Timing moved from Ch24 to Ch16 (Habit 3). The program now has five phases, and Phase 6 has been removed. All chapter text edits are merged and verified in `/book/`. The full change record is in `audit/food-timing-move-renumber-proposed.md`, including sections D (endnotes) and E (wiki), which are still open.

**Current book order:**

| Phase | Chapters |
|---|---|
| — | Ch01–Ch10 (unchanged; Ch09 = What Goes Wrong) |
| Phase 1 – get set up | Ch11 Feedback Loop, Ch12 Supplements, Ch13 Sleep Environment |
| Phase 2 – Remove the first three disruptors | Ch14 Caffeine (H1), Ch15 Alcohol (H2), Ch16 Food Timing (H3) |
| Phase 3 – Train your body clock | Ch17 Can't sleep routine (H4), Ch18 Morning Routine (H5), Ch19 Evening Routine (H6) |
| Phase 4 – Build your nervous system | Ch20 Meditation (H7), Ch21 Napping (H8), Ch22 Exercise (H9) |
| Phase 5 – Remove the final three disruptors | Ch23 Social Media (H10), Ch24 Hydration (H11), Ch25 Sugar & Food Sensitivities (H12) |
| — | Ch26 What Happens Next |

The 3/3/6 pillar split (see `derived/three-pillars-mapping.md`) is: body clock = Can't sleep, Morning, Evening; nervous system = Meditation, Napping, Exercise; disrupters = Caffeine, Alcohol, Food Timing, Social Media, Hydration, Sugar.

**Still open on the book side (me, by hand):** Meditation L7 should say "nineteen chapters in", not "eighteen". The filenames for ch16–ch24 still carry the old habit numbers. Check both before you start, and remind me if they're still open.

## Task 1: endnotes (`book/endnotes.md`, delivered as a clean copy)

The endnote headings use the **pre-Ch09 numbering**, which is one behind the old order even before this move. Map them by **title, not number**:

| Current heading in endnotes.md | Correct heading |
|---|---|
| Chapter 1–8 | unchanged (check the titles match) |
| Chapter 10 — Your Feedback Loop | Chapter 11 |
| Chapter 11 — Supplements | Chapter 12 |
| Chapter 12 — Your Sleep Environment | Chapter 13 |
| Chapter 13 — Caffeine | Chapter 14 |
| Chapter 14 — Alcohol | Chapter 15 |
| Chapter 23 — Food Timing | **Chapter 16**, and move the whole section to sit after Alcohol |
| Chapter 15 — Can't-Sleep Routine | Chapter 17 |
| Chapter 16 — Morning Routine | Chapter 18 |
| Chapter 18 — Meditation | Chapter 20 |
| Chapter 19 — Napping | Chapter 21 |
| Chapter 20 — Exercise | Chapter 22 |
| Chapter 22 — Hydration | Chapter 24 |
| Chapter 24 — Sugar and Food Sensitivities | Chapter 25 |

Also check the body text. For example, L107 "covered separately in Chapter 14" (alcohol) should say Chapter 15. Grep for every `Chapter \d+` in the notes and check each against the topic. Check whether any note needs moving because the chapter it annotates changed; the only move expected is Food Timing. Keep the neutral encyclopedia voice. Deliver the result to `audit/endnotes (renumbered clean).md`, give me a before/after table of every change, and I'll merge it.

After I merge, update `derived/claims-knowledge-base.md` wherever its entries cite chapter numbers, so the knowledge base and the endnotes agree.

## Task 2: wiki, index and live derived files (edit directly)

The wiki uses the **pre-move (post-Ch09) numbering**. For example, `ch24` means Food Timing and `ch16` means Can't sleep. Apply this mapping to every `chNN` / `ChNN` reference:

| Old | New |
|---|---|
| ch01–ch15 | unchanged |
| ch24 (Food Timing) | ch16 |
| ch16 (Can't sleep) | ch17 |
| ch17 (Morning) | ch18 |
| ch18 (Evening) | ch19 |
| ch19 (Meditation) | ch20 |
| ch20 (Napping) | ch21 |
| ch21 (Exercise) | ch22 |
| ch22 (Social Media) | ch23 |
| ch23 (Hydration) | ch24 |
| ch25, ch26 | unchanged |

**Method:** do it in a single pass with a mapping, never sequential find/replace, because ch16 becomes ch17 and ch17 becomes ch18 and so on. Before replacing, spot-check that each reference's topic matches its old chapter. Flag anything that already looked wrong instead of silently shifting it. Also update habit numbers ("Habit 11" → "Habit 3" etc.), phase names and numbers (any "Phase 6" → gone; Can't sleep is now Phase 3), and `appears_in` ordering where it's listed by chapter.

**Files with ch16–ch24 references (found 2026-09-25, about 225 hits):** `index.md`, and in `wiki/`: adenosine, anecdote-mountain-biking, bed-sleep-association, calming-activating-systems, cant-sleep-routine, circadian-rhythm, cortisol, dopamine, evening-routine, exercise-and-sleep, food-timing, hormone-misalignment, hydration-and-sleep, light-and-sleep, meditation-and-body-scan, morning-routine, napping, sleep-as-a-system, sleep-environment, sleep-stages, sleep-tracker, sleep-window, social-media-and-sleep, vagus-nerve. Also `derived/compile-docx-prompt.md` and `derived/three-pillars-mapping.md` (it uses `Ch16` style and still shows the old phase table). Re-grep in case anything was missed.

**Leave these alone:** historical or dated files, including `log.md` entries, older `continuation-prompt-*.md` files, `fb-trial-recruitment-post.md` and everything under `audit/archive/`. They record what was true at the time.

## Finish

- Update `CLAUDE.md`'s file map, which still points to `audit/endnotes-final.md` and `audit/continuity-coherence-pass.md`. Both were archived on 2026-09-24 to `audit/archive/2026-09-24/`.
- Once everything is merged, move `audit/food-timing-move-renumber-proposed.md` and `audit/clean-food-timing-move/` to `audit/archive/`.
- Give me a short summary: files touched, number of references changed, and anything flagged.
