# Audit — Chapter 1 ("The Weight of It")

Run: 2026-06-09. Full audit, no confirmation gates. Surfacing typos and issues of
criticality > 1/5 only. Lower-criticality stylistic notes omitted by request.
Proposals only — `/book/` is read-only.

---

## CRITICAL — manuscript corruption

**C1 (5/5) — Chat artifacts pasted into the manuscript.**
Line 15 of `ch01.md` currently reads:

> Please give me a clean copyClaude responded: The nights were unpredictable.The nights were unpredictable. Some nights I would fall asleep as soon as my head hit the pillow...

An editing-session fragment ("Please give me a clean copyClaude responded:") and a
duplicated "The nights were unpredictable." have been pasted into the body. This must be
cleaned to the intended opening of the paragraph:

> ~~Please give me a clean copyClaude responded: The nights were unpredictable.The nights were unpredictable.~~ **The nights were unpredictable.** Some nights I would fall asleep as soon as my head hit the pillow. Others I would lie awake for hours.

---

## Typos / grammar (> 1/5)

**T1 (4/5) — Line 29.** "There were times I would gave up for a while."
> There were times I would ~~gave~~ **give** up for a while.

**T2 (4/5) — Line 33.** Missing "to."
> But I was always foggy, barely able **to** follow the words on the page.

**T3 (2/5) — Line 33.** Double spaces in two places.
> It should have been ~~  ~~ one of the good parts of the day.
> I would read aloud and not take them in. ~~ ~~ My children were right there...

**T4 (2/5) — Line 19.** Stacked double-qualifier "often … usually."
> These helped, but ~~often~~ a semi-lucid 15-minute rest was usually all I could achieve.

(Also note "15 minute" → "15-minute" as a compound modifier, per the style notes' numeral conventions.)

---

## Six-category review (only issues > 1/5)

### Contradictions
None above threshold.

### Cadence and flow
**F1 (2/5) — Line 19.** The nap paragraph is the densest block in an otherwise
well-spaced chapter, and "often … usually" (see T4) makes one sentence stumble. Fixing
T4 resolves it; no structural change needed.

### Weak points
None above threshold. The chapter is memoir register (voice baseline) and earns its
claims through lived detail.

### Over-explaining
**O1 (2/5) — Line 35.** "That was it. That was the whole problem, the way it took over
every important moment of my life." Lands right after the reading-to-children scene,
which has already shown exactly this. The restatement risks telling the reader what the
scene just made them feel. Per style notes ("show the mechanism, don't name the
feeling"; "trust the reader"), consider trimming:

> ~~That was it. That was the whole problem, the way it took over every important moment of my life.~~

Left as a proposal — the short declarative may be a deliberate beat-landing the author
wants. Flagged, not pressed.

### Repetition
**R1 (2/5) — Line 7.** "Getting irritated by things that really shouldn't have irritated
me." The irritated/irritated echo reads as an accidental repeat rather than the author's
deliberate emphasis style.
> Getting irritated by things that really shouldn't have **bothered** me.

(Cross-chapter check: "afternoon dip," "compensatory behaviours," and "sleep deficit"
all recur per `index.md`, but ch01 is their first/establishing appearance — no
over-exposure to flag here.)

### Abrupt transitions
None above threshold.

---

## Summary
- 1 critical manuscript-corruption issue (C1) — clean the pasted chat text on line 15.
- 2 clear grammar errors (T1 "would gave," T2 missing "to").
- Minor mechanical/stylistic items (double spaces, double-qualifier, one repeat) at 2/5.
- Two judgment-call proposals (O1, R1) flagged but not pressed.
