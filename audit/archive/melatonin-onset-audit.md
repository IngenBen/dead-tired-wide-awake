# Audit — Melatonin onset vs. peak: contradictions and proposed additions

*Run: 2026-06-05*
*Scope: ch06 (Melatonin), ch08 (Dopamine/Scrolling). Cross-checked: ch07, ch16, ch21.*
*Trigger: conversation surfacing that the sleep window tracks melatonin's onset/rate of rise, not its peak level.*

> **CORRECTION — 2026-06-11.** This audit originally stated melatonin "doesn't peak until 2–3am." That figure was wrong. The author's authoritative timeline (10–11pm bedtime) is: rise begins ~7:30–8pm → steepest rise (the window) ~9pm–midnight, centred on bedtime → **peak ~midnight–1am** → stays elevated to ~2am → **declines from ~2am** → baseline ~6am. The "2–3am" instances below have been corrected to "midnight–1am." **The core finding of this audit is unaffected and still correct:** the window is the steep *rise/onset*, not the peak, so "missing the window = melatonin peaked and fell" remains wrong. Only the peak *clock time* changed. (Knock-on: this corrected timeline makes "melatonin declines around 2–3am" a *valid* basis for the 2/3am wake-up idea — see `melatonin-2-3am-wakeup-placement.md`, Clash 1, now reversed.)

---

## Summary

In three places the book describes missing the sleep window as melatonin having *peaked and begun to fall*. This is incorrect — melatonin doesn't peak until around midnight–1am, well after sleep onset, and only declines from ~2am. The window closes because the rate of rise slows and the convergence of signals weakens, not because melatonin peaks.

Finding 1 also surfaces a secondary problem: the existing line defining the window ("The steepest part of melatonin's rise is brief — thirty to sixty minutes, roughly. That's the window.") is too reductive. The window is about convergence of multiple signals; pinning it to a precise duration of melatonin's rate of change overstates what we know. Proposed fix folds the correct science into the convergence description already on the page.

Finding 2 also adds shift work as a third melatonin use case (currently missing), with a short callback to the jet lag explanation rather than repeating it.

---

## Finding 1 — Internal contradiction in ch06 (lines 37–45)

**Type:** Contradiction (within chapter) + inaccurate claim
**Location:** ch06, lines 37–45

The passage has two problems. First, line 39 ("The steepest part of melatonin's rise is brief — thirty to sixty minutes, roughly. That's the window.") pins the window to a precise duration of a single hormone's rate of change — this is too reductive. The window is about convergence of multiple signals, as the sentence immediately before it correctly states. Second, line 41 says missing the window means the signal has "passed its peak" — but melatonin doesn't peak until around midnight–1am, contradicting the "steepest rise" framing two lines earlier.

The fix: cut the "thirty to sixty minutes" sentence entirely and replace it with language that keeps the convergence framing, adds the onset-not-peak point, and explains what missing the window actually means. The "Miss it" paragraph that follows can be trimmed of its now-redundant middle sentences.

**Current text:**

> The sleep window opens when several signals converge: melatonin rising steeply, adenosine high from a full day of wakefulness, cortisol low, core body temperature falling. When those conditions align, ~~sleep comes easily.~~
>
> ~~The steepest part of melatonin's rise is brief — thirty to sixty minutes, roughly. That's the window.~~
>
> Miss it, and the alignment breaks. ~~Adenosine doesn't stand down; the sleep pressure is still there. But the melatonin signal has passed its peak and the other conditions have shifted.~~ You're exhausted and alert simultaneously. Tired but wired.

**Proposed fix:**

> The sleep window opens when several signals converge: melatonin rising steeply, adenosine high from a full day of wakefulness, cortisol low, core body temperature falling. When those conditions align, **you feel the strongest pull toward sleep. Even though melatonin and adenosine continue to rise — and adenosine will keep rising if you stay awake — they are not rising as quickly, and the pull is not as strong. At this point, if you have Wake Executives who don't want to finish work, you've missed the window.**
>
> Miss it, and the alignment breaks. ~~Adenosine doesn't stand down; the sleep pressure is still there. But the melatonin signal has passed its peak and the other conditions have shifted.~~ You're exhausted and alert simultaneously. Tired but wired.

---

## Finding 2 — Error in the supplement scenario + missing third use case (ch06, lines 59–63)

**Type:** Factual error / internal contradiction + gap
**Location:** ch06, lines 59–63 (also present in ch06-proposed.md lines 64–68 — error was carried forward into the existing proposed edit)

The supplement scenario for "missed your window" says the melatonin signal has peaked and begun to fall. For a typical missed-window — a social event running late, pushing past a 10–11pm sleep window — melatonin is still rising toward its midnight–1am peak. It has not peaked. The supplement reinforces the still-rising signal; it doesn't create a new peak after a fall.

Additionally, the chapter currently lists two scenarios for taking melatonin. Shift work belongs as a third — it is a sustained clock displacement, more like jet lag than a one-off missed window. The two are close enough that the shift work entry can be a short callback rather than a full re-explanation.

**Current text (ch06, lines 59–63):**

> I now know Melatonin is useful in ~~two~~ specific scenarios.
>
> The first is when you've missed your window. If you've pushed past your normal sleep time — a social event, ~~shift work,~~ something that ran long — the clock hasn't stopped. It's moved on without you. ~~Your melatonin signal has peaked and begun to fall.~~
>
> ~~A small dose at this point — 0.5 to 1mg, not the 5mg tablets most shops sell — can help to create a new peak in your body. Like you're sending a reminder: its sleep time now.~~
>
> The second is jet lag. When you cross time zones, the melatonin signal isn't disrupted so much as stranded. Your body is still signalling night according to where you departed. A small dose taken at local bedtime in the new time zone helps nudge the clock toward where it needs to be. This is melatonin doing exactly what it was designed to do: acting as a timing signal for a system that has temporarily lost its reference point.

**Proposed fix:**

> I now know melatonin is useful in **three** specific scenarios.
>
> The first is when you've missed your window. If you've pushed past your normal sleep time — a social event, something that ran long — the clock hasn't stopped. It's moved on without you. ~~Your melatonin signal has peaked and begun to fall.~~ **The steep rise has passed. The body's own timing signal has weakened.**
>
> ~~A small dose at this point — 0.5 to 1mg, not the 5mg tablets most shops sell — can help to create a new peak in your body. Like you're sending a reminder: its sleep time now.~~ **A small dose — 0.5 to 1mg, not the 5mg tablets most shops sell — reinforces the signal: a short, sharp rise that tells the system sleep time is now.**
>
> The second is jet lag. When you cross time zones, the melatonin signal isn't disrupted so much as stranded. Your body is still signalling night according to where you departed. A small dose taken at local bedtime in the new time zone helps nudge the clock toward where it needs to be. This is melatonin doing exactly what it was designed to do: acting as a timing signal for a system that has temporarily lost its reference point.
>
> **The third is shift work. The mechanism is the same as jet lag — the clock isn't broken, it's stranded. Your body is signalling night according to the schedule it was set to, not the one you're now working. Same approach: a small dose at your new target sleep time helps nudge the clock toward where it needs to be.**

---

## Finding 3 — Error in ch08 (line 65)

**Type:** Factual error (same as Finding 1 / 2)
**Location:** ch08, line 65

The same "melatonin had started to fall" framing appears in the scrolling chapter, describing what happens when pre-bed screen use pushes the author past the sleep window.

**Current text:**

> Looking back, that pre-bed scrolling was almost certainly pushing me past my sleep window some nights. Elevated cortisol and enough dopamine to carry me through to the point where ~~melatonin had already started to fall~~. By the time I put the phone down, the window had closed.

**Proposed fix:**

> Looking back, that pre-bed scrolling was almost certainly pushing me past my sleep window some nights. Elevated cortisol and enough dopamine to carry me through to the point where ~~melatonin had already started to fall~~ **the steep rise had already passed**. By the time I put the phone down, the window had closed.

---

## Finding 4 — Missing explanation for small vs. large dose (ch06, dosing section)

**Type:** Gap / weak point
**Location:** ch06, lines 67–68 (the dose warning)

The chapter correctly recommends 0.5–1mg and warns against the 5mg tablets in shops, citing desensitisation as the risk. This is true but incomplete — it doesn't explain *why* a small dose is more effective, which leaves the recommendation feeling like a precaution rather than something the reader understands.

The onset/rate-of-rise insight explains it directly: a small dose creates a sharp, brief rise that mimics the onset signal the body is actually calibrated to respond to. A large dose floods receptors with a sustained high level — it doesn't replicate the signal pattern, and over time it blunts the body's sensitivity to melatonin's natural onset.

**Current text:**

> The first is dose. Most over-the-counter melatonin runs far higher than what the body naturally produces. Take too much, and residual melatonin can still be circulating by morning, producing grogginess. But this is a dose problem, not a melatonin problem. Research suggests 0.5mg is sufficient for most people. Much higher doses can lead to desensitisation.

**Proposed fix:**

> The first is dose. Most over-the-counter melatonin runs far higher than what the body naturally produces. Take too much, and residual melatonin can still be circulating by morning, producing grogginess. **And because the body responds to the rise rather than the level, a high dose doesn't increase the effect — it just extends it into the morning and gradually blunts your sensitivity to the natural signal.** ~~But this is a dose problem, not a melatonin problem. Research suggests 0.5mg is sufficient for most people. Much higher doses can lead to desensitisation.~~ **That's why 0.5mg works. It's enough to send the signal. More isn't more.**

---

## Recommended action order

1. **Rewrite the window definition** in ch06 (Finding 1) — fold the onset-not-peak insight into the convergence description, cut the "thirty to sixty minutes" sentence, trim the "Miss it" paragraph.
2. **Fix the supplement scenario** in ch06 (Finding 2) — fix the "peaked and begun to fall" error, reframe the dose action, add shift work as third use case.
3. **Fix ch08 line 65** (Finding 3) — minor, one phrase.
4. **Consider the dose explanation** in Finding 4 — optional if Finding 2's new wording already makes the point sufficiently.

---

## Cross-chapter check

- **ch07**: "Cortisol and melatonin should work in opposition — in the evening as cortisol falls, melatonin rises." Accurate; no conflict.
- **ch16**: "The countdown to evening melatonin release starts later." Accurate; no conflict.
- **ch21**: "melatonin beginning its rise" — accurate framing, no conflict.
- **ch08**: Error found (Finding 3 above).
- **ch11**: Melatonin not in the supplements chapter — this is consistent and correct; the book treats it as a timing tool in ch06 rather than a sleep supplement.

---

*No edits to /book/. All changes are proposals for the author to apply.*
