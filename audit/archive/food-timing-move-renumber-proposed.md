---
title: Move Food Timing to after Alcohol — renumbering and cross-reference changes
type: audit
status: proposal
date: 2026-09-25
note: Proposals only. /book/ is read-only — apply by hand. Line numbers are against the current /book/ files (before any move).
---

# Move Food Timing (ch24) to after Alcohol (ch15)

**Decision (author, 2026-09-25):** Food Timing becomes Habit 3, the third disrupter in Phase 2, alongside Caffeine and Alcohol. Sugar stays late (ch25 explains why).

## New order

| Before | After |
|---|---|
| Ch14 – Habit 1: Caffeine | Ch14 – Habit 1: Caffeine |
| Ch15 – Habit 2: Alcohol | Ch15 – Habit 2: Alcohol |
| Ch24 – Habit 11: Food Timing | **Ch16 – Habit 3: Food Timing** |
| Ch16 – Habit 3: Can't sleep routine | Ch17 – Habit 4: Can't sleep routine |
| Ch17 – Habit 4: Your Morning Routine | Ch18 – Habit 5: Your Morning Routine |
| Ch18 – Habit 5: Your Evening Routine | Ch19 – Habit 6: Your Evening Routine |
| Ch19 – Habit 6: Meditation | Ch20 – Habit 7: Meditation |
| Ch20 – Habit 7: Napping | Ch21 – Habit 8: Napping |
| Ch21 – Habit 8: Exercise | Ch22 – Habit 9: Exercise |
| Ch22 – Habit 9: Social Media | Ch23 – Habit 10: Social Media |
| Ch23 – Habit 10: Hydration | Ch24 – Habit 11: Hydration |
| Ch25 – Habit 12: Sugar | Ch25 – Habit 12: Sugar (unchanged) |

Ch01–Ch15 and Ch25–Ch26 keep their numbers.

## Phase structure (decided 2026-09-25)

| Phase | Chapters (new numbers) |
|---|---|
| Phase 1 – Get set up | Ch11 Feedback Loop, Ch12 Supplements, Ch13 Sleep Environment (unchanged) |
| Phase 2 – Remove the first three disruptors | Ch14 Caffeine, Ch15 Alcohol, Ch16 Food Timing |
| Phase 3 – Train your body clock | Ch17 Can't sleep routine, Ch18 Morning Routine, Ch19 Evening Routine |
| Phase 4 – Build your nervous system | Ch20 Meditation, Ch21 Napping, Ch22 Exercise |
| Phase 5 – Remove the final three disruptors | Ch23 Social Media, Ch24 Hydration, Ch25 Sugar & Food Sensitivities |

**Phase 6 is removed entirely.** The program now has five phases. The changes this needs are in section G.

## A. Chapter headings and file names

| # | File (current) | Before | After |
|---|---|---|---|
| A1 | ch24 - Habit 11 - Food Timing.md | `# Chapter 24 - Habit 11: Food Timing` | `# Chapter 16 - Habit 3: Food Timing` (file → `ch16 - Habit 3 - Food Timing.md`) |
| A2 | ch16 - Habit 3 - Can't sleep routine.md | `# Chapter 16 - Habit 3: Can’t sleep routine` | `# Chapter 17 - Habit 4: Can’t sleep routine` (file → `ch17 - Habit 4 - …`) |
| A3 | ch17 - Habit 4 - Your Morning Routine.md | `# Chapter 17 - Habit 4: Your Morning Routine` | `# Chapter 18 - Habit 5: Your Morning Routine` |
| A4 | ch18 - Habit 5 - Your Evening Routine.md | `# Chapter 18 - Habit 5: Your Evening Routine` | `# Chapter 19 - Habit 6: Your Evening Routine` |
| A5 | ch19 - Habit 6 - Meditation.md | `# Chapter 19 - Habit 6: Meditation` | `# Chapter 20 - Habit 7: Meditation` |
| A6 | ch20 - Habit 7 - Napping.md | `# Chapter 20 - Habit 7: Napping` | `# Chapter 21 - Habit 8: Napping` |
| A7 | ch21 - Habit 8 - Exercise.md | `# Chapter 21 - Habit 8: Exercise` | `# Chapter 22 - Habit 9: Exercise` |
| A8 | ch22 - Habit 9 - Social Media.md | `# Chapter 22 - Habit 9: Social Media` | `# Chapter 23 - Habit 10: Social Media` |
| A9 | ch23 - Habit 10 - Hydration & waking up to pee.md | `# Chapter 23 - Habit 10: Hydration & waking up to pee` | `# Chapter 24 - Habit 11: Hydration & waking up to pee` |

## B. In-text chapter references

Rows marked ⚠ are **already wrong today** (left over from the earlier ch09 insertion). They are corrected to the right chapter under the new order.

| # | Location (current file, line) | Before | After |
|---|---|---|---|
| B1 | ch05 L41 (stress → Meditation) | That's Chapter 19. | That's Chapter 20. |
| B2 | ch05 L45 (irregular schedule → Morning/Evening) | That's Chapters 17 and 18. | That's Chapters 18 and 19. |
| B3 | ch05 L47 (screens → Social Media) | That's Chapter 22. | That's Chapter 23. |
| B4 ⚠ | ch08 L45 (what to watch → Can't sleep / Evening) | …what to watch and what to avoid in Chapters 15 and 17. | …what to watch and what to avoid in Chapters 17 and 19. |
| B5 | ch13 L75 (bed is for sleep → Can't sleep) | There's a fuller version of this in Chapter 16, where it matters most… | There's a fuller version of this in Chapter 17, where it matters most… |
| B6 ⚠ | ch17 Morning L54 (→ Evening) | Then turn to Chapter 17, where we build the other end of the day. | Then turn to Chapter 19, where we build the other end of the day. |
| B7 ⚠ | ch19 Meditation L119 (1st) | …the middle-of-the-night routine from Chapter 15, meditation now belongs… | …the middle-of-the-night routine from Chapter 17, meditation now belongs… |
| B8 ⚠ | ch19 Meditation L119 (2nd) | Get up and follow the rest of the Chapter 15 routine from there. | Get up and follow the rest of the Chapter 17 routine from there. |
| B9 | ch21 Exercise L48 (→ Morning) | …it's been there since Chapter 17. | …it's been there since Chapter 18. |
| B10 | ch22 Social L38 (→ Can't sleep) | …the can't-sleep routine from Chapter 16 is what takes over… | …the can't-sleep routine from Chapter 17 is what takes over… |
| B11 | ch22 Social L46 (→ Evening) | …after Chapter 18, the phone is away once the wind-down begins. | …after Chapter 19, the phone is away once the wind-down begins. |

**Checked, no change needed:** ch04 L5 (Ch3); ch05 L33 (Ch4, Ch7), L39 and L57 (Ch14), L43 (Ch13), L65 (Ch7); ch09 L5 (Ch4), L46 and L62 (Ch6); ch10 L13 and L15 (Ch4), L47 (Ch11); ch12 L14 (Ch7); ch15 L25 (Ch11); ch16 L28 (Ch7), L52 (Ch1); ch19 L27 and L65 (Ch7); ch21 L6 (Ch2); ch22 L22, L28, L32 (Ch8).

## C. Wording changed by the move (not numbers)

| # | Location | Before | After (suggested; rewrite in your voice) |
|---|---|---|---|
| C1 | Food Timing L35 (closing line) | The next chapter looks at sugar: specifically what happens when blood sugar spikes and crashes in the hours before bed, and why that cortisol rebound is waking more people up at two or three in the morning than they realise. | Replace with a lead-in to the Can't sleep routine, e.g. "The next chapter is the one most people want first: what to do when you're lying awake anyway." (Optionally move the sugar teaser to the end of Hydration, which will now come before Sugar.) |
| C2 | Social Media L11 | Food, hydration, sugar: this phase is about what you put into your body. | Hydration and sugar: the rest of this phase is about what you put into your body. |
| C3 (optional) | Food Timing L31 | It fits where you'd expect. Light sets the clock. Sleep timing reinforces it. Food timing keeps everything aligned. | The morning and evening routines haven't been covered yet at this point. The line still works as science from ch06/ch09, but you could add "You'll build the first two in Phase 3." |

**Checked, no change needed:** Alcohol → Food Timing now flows well ("It's a bit like alcohol though…"). Can't sleep's "Phase 3 begins in the morning." is still true. Ch14's Phase 2 intro doesn't list its habits. Ch25's "That's why sugar comes this late in the program" and "Twenty-five chapters, twelve habits" stay as they are.

## G. Phase headings and phase wording

Heading wording follows the structure agreed on 2026-09-25. Adjust the exact titles to your preferred style.

| # | Location (current file, line) | Before | After |
|---|---|---|---|
| G1 | ch14 Caffeine L1 | # Phase 2 – Remove Disruption | # Phase 2 – Remove the first three disruptors |
| G2 | ch17 Morning L1 | # Phase 3 – Train your body clock | *(delete here; the heading moves to the start of the Can't sleep chapter)* |
| G3 | ch16 Can't sleep, top (new ch17) | *(no phase heading)* | # Phase 3 – Train your body clock *(placed above "# Chapter 17 - Habit 4: Can't sleep routine")* |
| G4 | ch16 Can't sleep L64 (closing line) | Phase 3 begins in the morning. | The line no longer works, because Phase 3 now starts with this chapter. Suggest: "Next, the morning." or "The rest of Phase 3 begins in the morning." |
| G5 (optional) | ch16 Can't sleep, top | — | Phase 4 opens with a short phase intro ("The focus of this phase is…"). If you want Phase 3 to match, add 1–2 lines, e.g. "The focus of this phase is to train your body clock: what you do in the night, the morning and the evening. Three habits, all anchoring the same clock." |
| G6 | ch19 Meditation L1 | # Phase 4 – train your nervous system | # Phase 4 – Build your nervous system |
| G7 | ch22 Social Media L1 | # Phase 5 – optimise your inputs (remove remaining  disruptors) | # Phase 5 – Remove the final three disruptors |
| G8 | ch23 Hydration L2 | # Phase 6 – optimise your inputs | *(delete the heading)* |
| G9 | ch23 Hydration L5 | Hydration is the first chapter in Phase 6, and probably the one that feels least like a sleep habit. | Hydration is the second habit in Phase 5, and probably the one that feels least like a sleep habit. |
| G10 | ch23 Hydration L35 | …and removing friction is the whole point of Phase 6. | …and removing friction is the whole point of Phase 5. |
| G11 | ch10 L35 | Move at roughly a phase a week and you could be through them in six weeks… | Move at roughly a phase a week and you could be through them in five weeks… |

**Checked, no change needed:** ch10 L37 ("the habits in phase 4") is still Meditation, Napping and Exercise. ch10 L39 ("before Phase 1 begins"), ch11 L1 (Phase 1 heading) and ch14 L6 ("Phase 1 was about getting set up… Phase 2 does") are fine. ch18 Evening L43 ("Phase 3 is now in place. You have a morning anchor and an evening one.") still closes Phase 3. ch19 Meditation L3 (phase intro) is fine. ch22 Social L3 ("Phase 2 cleared the biggest disruptors. Phase 5 clears the rest.") and L9 ("the first habit in Phase 5") are fine. C2 already fits the new Phase 5 (Social, Hydration, Sugar).

## D. endnotes.md *(deferred: do after the book)*

⚠ All endnote headings from Chapter 10 onward still use the **pre-ch09** numbering, so they are off by one today, before this move.

| # | Location | Before | After |
|---|---|---|---|
| D1 ⚠ | L107 | …which is why it is covered separately in Chapter 14. | …which is why it is covered separately in Chapter 15. |
| D2 ⚠ | L214 | ## Chapter 10 — Your Feedback Loop | ## Chapter 11 — Your Feedback Loop |
| D3 ⚠ | L260 | ## Chapter 11 — Supplements | ## Chapter 12 — Supplements |
| D4 ⚠ | L305 | ## Chapter 12 — Your Sleep Environment | ## Chapter 13 — Your Sleep Environment |
| D5 ⚠ | L358 | ## Chapter 13 — Caffeine | ## Chapter 14 — Caffeine |
| D6 ⚠ | L392 | ## Chapter 14 — Alcohol | ## Chapter 15 — Alcohol |
| D7 | L627 (move whole section to sit after Alcohol) | ## Chapter 23 — Food Timing | ## Chapter 16 — Food Timing |
| D8 | L458 | ## Chapter 15 — Can't-Sleep Routine | ## Chapter 17 — Can't-Sleep Routine |
| D9 | L492 | ## Chapter 16 — Morning Routine | ## Chapter 18 — Morning Routine |
| D10 | L509 | ## Chapter 18 — Meditation | ## Chapter 20 — Meditation |
| D11 | L547 | ## Chapter 19 — Napping | ## Chapter 21 — Napping |
| D12 | L565 | ## Chapter 20 — Exercise | ## Chapter 22 — Exercise |
| D13 | L597 | ## Chapter 22 — Hydration | ## Chapter 24 — Hydration |
| D14 ⚠ | L645 | ## Chapter 24 — Sugar and Food Sensitivities | ## Chapter 25 — Sugar and Food Sensitivities |

## E. Outside /book/ *(deferred: do after the book and endnotes)*

- `wiki/`, `derived/`, `index.md`: about 225 `chNN` references across 32 files point at ch16–ch24. I'll renumber these after the book changes are made.
- `derived/three-pillars-mapping.md`: move Food Timing into Phase 2 and renumber.
- `Sleep Incorporated.docx` / `sleep_inc_manuscript.docx`: rebuild after the /book/ edits.

## F. Related flags (not caused by the move)

- ~~Phase 5 vs Phase 6~~: resolved. Phase 6 is removed (section G).
- ~~Can't sleep routine in Phase 2~~: resolved. Phase 3 now opens with it (G2/G3).
- ch16 L28: "We discussed this briefly in the Chapter 7 - Cortisol." → "…briefly in Chapter 7."
- ch26 L11: "a three-hour gap before dinner" probably means a three-hour gap between dinner and bed.
