# Audit — Executive Metaphor vs. Hormone Names: Reinforcement or Cognitive Load?

**Date:** 2026-06-29 · **Type:** AUDIT (terminology / coherence)
**Scope:** The "Sleep Incorporated" executive metaphor from Ch04 onward, and its interleaving
with the literal hormone names (adenosine, melatonin, cortisol, dopamine).
**Question asked:** Does referring to the hormones sometimes by name and sometimes by the
executive grouping reinforce the concept, or increase the reader's cognitive load?
**Status:** Proposals only. Per CLAUDE.md, `/book/` is read-only — every fix below is for the
author to apply by hand.

---

## Verdict

**On balance it reinforces — net asset, not net cost.** The dual naming is dual-coding (a
technical term paired with a functional role), the cast is small (4 hormones, 2 teams), and the
mapping is consistent and never reassigned. But there is **one specific, fixable mechanic that
genuinely raises load**, plus two smaller contributors. None of the fixes require weakening or
removing the metaphor.

---

## The mapping under review

Established in Ch04 and held consistently thereafter:

| Hormone | Role label | Team |
|---|---|---|
| Adenosine | sleep-pressure executive | Sleep Executive |
| Melatonin | sleep-timing executive | Sleep Executive |
| Cortisol | waking-energy executive | Wake Executive |
| Dopamine | motivation executive | Wake Executive |

Frequency of the word "executive" by chapter: Ch04 = 20 (intro), Ch05–08 = 2/4/6/5 (the hormone
chapters), Ch09–15 ≈ 0 (dormant), Ch16–25 = scattered (6/5/3/1/3/2/1/0/2/1). The term is
front-loaded, goes quiet through the early-habit chapters, then returns.

---

## Why it mostly reinforces (keep this)

1. **Consistent 1:1 mapping.** Adenosine is *always* the sleep-pressure executive; cortisol is
   *always* a wake executive. A metaphor that never reassigns its referents is teachable — the
   reader builds the lookup table once and it stays valid for 26 chapters.
2. **Dual-coding adds function to an opaque name.** "Cortisol" means nothing to a lay reader;
   "Wake Executive running the day shift" (Ch07 ¶ "Cortisol is a Wake Executive — the one running
   the day shift") encodes what it does. Repeated pairing aids retention rather than competing
   with it.
3. **Small cast, within working memory.** Four entities in two teams — not a sprawling org chart.
4. **The team label does work the names can't.** The book's thesis is *alignment*: sleep happens
   when the sleep team beats the wake team at bedtime. "The Wake Executive never fully leaves the
   building" (Ch07) expresses a collective dynamic with agency and imagery; the literal version
   ("cortisol and dopamine remain elevated") is wordier and flat.
5. **The switching is mostly motivated.** Later chapters use the **hormone name** when a specific
   mechanism is in play (adenosine + napping, Ch19; cortisol + exercise, Ch20) and the **team
   label** when the collective behaviour is the point (missed window, Ch06). That is the metaphor
   pulling its weight, not noise.

---

## Findings (where load is genuinely added)

### M1 — "the Wake Executive" (singular) vs "the Wake Executives" (plural) mean different things — HIGH

The same term, one letter apart, points to two referents:

- **Plural = the pair (cortisol + dopamine).** Ch06 ¶ "the Wake Executives are still at their
  desks… The Wake Executives stay elevated, spike unexpectedly, refuse to go home." Ch16 ¶8 "the
  chaos I was causing for my Sleep and Wake Executives." Ch17 ¶3 "the Wake Executives are ready to
  hand over to the Sleep Executives."
- **Singular = cortisol specifically.** Ch20 ¶9 "The Wake Executive working flat out… he was
  designed to do"; ¶13 "The Wake Executive clocks off"; ¶15 "The Wake Executive wasn't clocking
  off — he was burning the candle at both ends" (dopamine is not in play during exercise). Ch18 ¶
  "the cortisol that was keeping the Wake Executive at his desk"; ¶ "the Wake Executive already
  clocked off." Ch07 ¶ "the Wake Executive never fully leaves the building" (in a cortisol passage).

**Why it's load:** when the singular appears, a careful reader has to resolve "is this cortisol
alone, or the team?" — a stop the dual naming itself does not cause. The gendered "he/his" deepens
the imagery but commits the singular further.

**Proposed fix:** reserve plural **"Wake Executives"** for the pair. When the referent is cortisol
alone, name it on first use in the passage — e.g. "cortisol, your Wake Executive" — then the
shorthand is unambiguous for the rest of that chapter. (Ch17 ¶5 already models this well: "cortisol
— your primary Wake Executive.") Affected passages: Ch07, Ch18, Ch20.

### M2 — Recall gap: metaphor goes dormant Ch09–15, returns cold in Ch16 — MEDIUM

The term is dense in Ch04–08, then near-absent for roughly seven chapters, then "Sleep and Wake
Executives" reappears in Ch16 ¶8 with no re-anchor. A reader arriving there is furthest from the
Ch04 definition, so the recall tax peaks exactly where the reminder is thinnest.

**Proposed fix:** a one-clause re-anchor at the first reuse after the gap (early Ch16) — e.g. a
parenthetical naming the four, or "your wake executives (cortisol and dopamine)". Costs a line;
removes the "who were those again?" stall for the whole back half of the book.

### M3 — Dopamine-as-*Wake* Executive fights a reader prior — LOW

Most readers file dopamine under reward/motivation, not wakefulness, so its team assignment takes
extra encoding. Ch08 ¶ "the dopamine Wake Executive activating, indifferent to the fact that sleep
should be happening" is correct but leans on a grouping the reader may not yet accept.

**Proposed fix:** one sentence in Ch08 heading off the reaction — acknowledge the reward
association, then explain why, for sleep, dopamine sits on the wake team (it keeps the system
"stimulated and searching," Ch04). Turns a potential snag into reinforcement.

---

## Summary of recommendations

1. **Keep the dual system.** It is a net asset; do not strip names or metaphor.
2. **Fix M1 (singular/plural):** reserve plural for the pair; name cortisol when it's cortisol
   alone. Highest-value, lowest-cost change.
3. **Fix M2:** add a one-clause re-anchor at the first reuse in Ch16.
4. **Fix M3:** one pre-emptive sentence in Ch08 on why dopamine is a wake executive.
5. **House style going forward:** in each hormone chapter, lead the first mention with *name +
   role*; thereafter either form alone is safe within that chapter.

---

## Appendix — Marked-up paragraphs (proposals, grouped by chapter)

**Display key:** **bold** = added wording, ~~strikethrough~~ = removed wording. Surrounding
paragraphs are shown unchanged, for context. Paragraph numbers count blank-line-separated blocks
from the top of each chapter file. Per CLAUDE.md these are proposals only — for the author to
hand-apply to `/book/`, never written there directly. Quotes below are from the live OneDrive copies.

### Chapter 7 — Cortisol (finding M1)

Within Ch07 the whole chapter is about cortisol, so singular "Wake Executive" reads clearly. The
one spot worth tightening is ¶61, where plural "Sleep Executives" and singular "Wake Executive"
sit in the same sentence:

> *(prev, ¶61 opening — unchanged)* …Every piece of stimulation is another small bump. Over time, those bumps accumulate. Baseline cortisol creeps up. The evening decline gets shallower.
>
> *(amended)* The Sleep Executives are trying to advance, but the Wake Executive **— cortisol —** never fully leaves the building.
>
> *(next, ¶63 — unchanged)* This makes returning to sleep harder. Which increases the frustration. Which spikes cortisol. Which makes sleep harder still…

### Chapter 8 — Dopamine (finding M3)

Pre-empt the "dopamine is the reward chemical, not a wake one" reaction at ¶39, where the
wake-executive label is first applied to it:

> *(prev, ¶37 — unchanged)* Over time, the thinking goes, this may recalibrate the reward system: fast, frequent, unpredictable spikes become the baseline, and slower signals — including those coming from the Sleep Executives — start to register as dull by comparison.
>
> *(amended, ¶39)* That's the sleep problem. **It can feel odd to file dopamine under "wake" — we know it as the reward chemical. But that's exactly the point: it keeps you stimulated and searching, and a mind still searching is not a mind letting go for the night.** The later you stay on the feed, the more it compounds — the dopamine Wake Executive activating, indifferent to the fact that sleep should be happening. And it explains a mistake I kept making.
>
> *(next, ¶41 — unchanged)* When I switched to more 'wholesome' content, it felt better, but it wasn't calming…

### Chapter 16 — Morning Routine (finding M2: re-anchor after the dormant stretch)

First reuse of the metaphor after seven near-silent chapters (Ch09–15); add a one-clause reminder
of who the four are:

> *(prev, ¶6 — unchanged)* …My job had flexibility on start time so I used it. I'd roll in late, make up the hours, it wasn't a problem. I thought I was being smart. Banking every hour of sleep I could get.
>
> *(amended, ¶8)* I was completely unaware of the chaos I was causing for my Sleep and Wake Executives **— adenosine and melatonin, cortisol and dopamine, the four we met earlier**. The problem is what happens to your body clock when the start of your day keeps moving around.
>
> *(next, ¶10 — unchanged)* Your body is not keeping score of hours the way you might think it is…

### Chapter 18 — Meditation (finding M1b: metaphor break — escalated)

**Correction to the first version of this audit.** I earlier wrote that ¶64 needed no change
because cortisol is named in the paragraph. That was wrong. ¶64 doesn't merely leave the referent
ambiguous — it **splits one entity into two**: cortisol is described as *"keeping the Wake
Executive at his desk,"* but cortisol **is** the Wake Executive, so it cannot also be the separate
force acting on it. This is a metaphor break, more serious than the M1 ambiguity. Fix by collapsing
the two back into one:

> *(prev, ¶62 — unchanged)* …Reverse engineer that: slow the breath deliberately, and the rest of the system responds, the vagus nerve sending a safety signal to the activating system.
>
> *(amended, ¶64)* This connects back to Chapter 7 — and to cortisol. Cortisol won't stop just because you ask it to; there's no direct switch. But the vagus nerve is a back channel to the system that governs it. A trained, well-exercised one helps turn down the cortisol response. When that happens at night — as the result of consistent daily training — the mind slows down because **the Wake Executive — cortisol —** ~~the cortisol that was keeping the Wake Executive at his desk~~ has finally left the building.
>
> *(next, ¶66 — unchanged)* Which means the breathing isn't asking your mind to be quiet. It's changing the chemistry that makes quiet possible.

(Alternative if you'd rather keep the "desk" beat over the Ch07 "leaves the building" callback:
"…the mind slows down because **the Wake Executive — cortisol —** has finally left his desk.")

**Scope check.** A sweep of every line containing both a hormone name and "executive" (Ch04, 07,
08, 15, 16, 17, 20, 24) confirms this "hormone X acts on the executive" doubling appears **nowhere
else** — the rest correctly treat cortisol/dopamine *as* the executive (e.g. Ch24 "cortisol is also
a Wake Executive"; Ch20 "Cortisol, the Wake Executive, working flat out").

*Note: the ¶122 cold-singular fix flagged in the first version has since been applied in the
manuscript — it now reads "the Wake Executive — cortisol — already clocked off." The Ch08, Ch16
and Ch20 proposals above have likewise been hand-applied.*

### Chapter 20 — Exercise (finding M1 — optional)

In Ch20 every singular "Wake Executive" is already anchored — cortisol is named in the same
paragraph (¶9 "Exercise spikes cortisol… The Wake Executive working flat out"). So **no change is
strictly required.** If you want belt-and-suspenders on the first use, replace the fragment so the
identity is explicit:

> *(prev, ¶7 — unchanged)* …I thought it was the price of doing something I loved. It wasn't. It was a mechanism I didn't yet understand.
>
> *(amended, ¶9)* Exercise spikes cortisol. That's not a flaw in the system — that's the point. Cortisol is what drives the effort. It sharpens focus, mobilises energy, keeps you moving when the body wants to stop. On a full day of downhill riding, I was running on it from the first run to the last. ~~The Wake Executive~~ **Cortisol, the Wake Executive,** working flat out, doing exactly what he was designed to do.
>
> *(next, ¶11 — unchanged)* The problem isn't the spike. The problem is what happens after.

---

*Sources: book/ch04–ch08, ch16–ch20 (Ch17/Ch20 passages verified against live OneDrive copies via
file reader). Cross-referenced: wiki/four-executives.md, wiki/sleep-incorporated-metaphor.md,
wiki/hormone-misalignment.md. Frequency counts via shell grep over /book/.*
