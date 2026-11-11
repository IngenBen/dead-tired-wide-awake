# Program Structure — Change Review

**Status:** proposals only. Nothing in `/book/` has been touched. Tick the ones you want and I'll write each to `/audit/` as a `-proposed` file (or update the existing one).

**Markup legend**
- ~~struck through~~ = text to **remove**
- **`+ … +`** (bold, plus-wrapped) = text to **add**
- "Context" shows the surrounding paragraph(s) so you can see the change in place.
- Tag after each heading: **[STILL PRESENT]** = the old framing is still in the live source · **[NEW DRAFT]** = net-new prose that hasn't been written yet (review harder).

Source note: where an `-proposed` file exists in `/audit/` (ch05–09), I quoted that, since it's the current working source per the project rules.

---

## Model — Activating / Calming, and the three habit jobs  **[DESIGN NOTE — agreed 2026-06-08]**

This note governs sections B, C, D, E. It's the reconciled model the A/C through-line rests on.

**The model (two states, swapping on a clock).** The nervous system is, at any moment, either *activating-dominant* or *calming-dominant* — two settings, not three. They're meant to **take turns on a daily schedule**: activating through the day, calming at night. Bad sleep is almost always a fault in that handover, and it fails one of two ways — the calming system has grown **too weak to take over**, or the two are **swapping on the wrong schedule** (the body clock has drifted).

**Why three habit jobs, not two states.** Every habit does one of three jobs, all serving the one goal (get calming to win at night, on time):

1. **Build calm** — strengthen the wind-down (meditation, can't-sleep routine, the winding-down half of the evening).
2. **Stop activating at the wrong time** — take your foot off the gas late in the day (caffeine, alcohol, social media, sugar). *Biggest, highest-leverage group in the book.*
3. **Regulate the clock** — keep the timing accurate so the swap lands on time (morning light, food timing, hydration, napping).

Jobs 1 and 2 are the **two ends of the same arousal axis** (build the brakes / ease off the gas); job 3 is the clock that decides *when*. That's how three jobs sit on top of two states without contradiction.

**The honest bridge (stated once, in Ch9).** Strictly, the body clock is a separate system from the nervous system, and the four executives don't all map neatly onto "activating vs calming." We bridge this with one admission — *"not a literal third gear; close enough to picture three jobs: wind down, stop winding up, keep time"* — which is enough for the reader to understand why each habit is recommended. Simplicity for the reader is the priority; accuracy is bridged, not chased.

**Decisions locked (2026-06-08):**
- *Three jobs, re-cut.* Not "Activating / Calming / Regulating" but **build calm / stop activating at the wrong time / regulate the clock**. The old "add energy in the day" bucket is dropped; morning light & exercise have a real energising effect but it just gets **mentioned in those chapters** — no standalone category.
- *Prose only — no per-habit tags.* The three are **defined once** in the Ch9 gateway (B1), **recapped** in Ch25 (F), and otherwise live as **flexible inline language** ("this one quiets things down," "a timing habit," "take your foot off the gas"). No fixed labels stamped on chapters — that would rebuild the "3 categories" framework we removed. So the "stop activating" idea stays a *verb phrase*, never a coined noun.
- *Relationship to the removed "3 categories."* This **replaces** it: the same three ideas, now subordinate to the single A/C through-line rather than a competing named taxonomy.
- *Naming drip + single vocabulary.* Ch4 (C1) seeds the idea **unnamed and label-free** — no coined term, to avoid colliding with the Wake/Sleep Executive split and front-running the autonomic mechanism (Ch7/Ch18). The **name** "activating/calming" arrives at Ch5 (C2), hung on caffeine. "Wind up / wind down" is the permanent plain-English gloss that travels *with* the names — never a separate concept that gets replaced.

**Copy convention (resolved 2026-06-08):**
- *Lowercase throughout.* "activating / calming" are plain language, not coined proper nouns — lowercase everywhere in running prose, including Ch18 (lowercase its existing "Activating System / Calming System" on apply).
- *Verb for effects; "system" for the trainable thing; never "side."* (Author preference, 2026-06-08.) Use the verb/adjective form for what an input does to you ("caffeine activates you," "the activating chemistry," "still activating when it should be calming"). Use **"activating system / calming system"** for the trainable thing that can be weak, built, or take over ("the calming system has grown too weak," "build the calming system," "a calming system strong enough to take over"). Same root word, two grammatical roles — one concept. "Side" is not used.
- *"Wind up / wind down"* stays as the permanent plain-English gloss alongside the named pair.

---

## A. Program structure — global

### A1. Headline: "16 habits" → "12 habits"  **[✅ APPLIED — audit/ch09-proposed.md + new audit/ch24-proposed.md]**
**Reason:** Agreed headline number. The book is the deliverable's count, not a framework — and the count changed.

Two live instances:

**Ch9** (`audit/ch09-proposed.md`, line 27):
> The result was ~~16~~ **`+ 12 +`** habits ~~across these six phases~~. Ready for you to work through in order, at your own pace. Slow is fast, if it means it sticks.

*(This line is also rewritten more fully in B2 below — apply whichever you prefer; they overlap.)*

**Ch24** (`book/ch24.md`, line 57):
> That's the last habit. Twenty-four chapters, ~~sixteen habits, six phases~~ **`+ twelve habits +`**. The program is built.

---

### A2. Number the habits 1–12 in chapter titles + ToC  **[✅ APPLIED — audit/a2-chapter-titles-proposed.md; format "Chapter # - Habit #: Name"]**
**Reason:** Makes the 12-count visible and gives the reader a progress spine. Phase 1 (Ch10–12) stays unlabelled setup — no numbers.

No chapter title currently carries a habit number, and there is no ToC file in `/book/`. Proposed titles (format is your call — shown here as `— Habit N:`):

| Chapter | Current title | Proposed |
|---|---|---|
| Ch10 | Your Feedback Loop | *(setup — no number)* |
| Ch11 | Supplements | *(setup — no number)* |
| Ch12 | Your Sleep Environment | *(setup — no number)* |
| Ch13 | Caffeine | Caffeine **`+ — Habit 1 +`** |
| Ch14 | Alcohol | Alcohol **`+ — Habit 2 +`** |
| Ch15 | Can't Sleep Routine | Can't Sleep Routine **`+ — Habit 3 +`** |
| Ch16 | Your Morning Routine | Your Morning Routine **`+ — Habit 4 +`** |
| Ch17 | Your Evening Routine | Your Evening Routine **`+ — Habit 5 +`** |
| Ch18 | Meditation | Meditation **`+ — Habit 6 +`** |
| Ch19 | Napping | Napping **`+ — Habit 7 +`** |
| Ch20 | Exercise | Exercise **`+ — Habit 8 +`** |
| Ch21 | Social Media | Social Media **`+ — Habit 9 +`** |
| Ch22 | Hydration & Waking to Pee | Hydration & Waking to Pee **`+ — Habit 10 +`** |
| Ch23 | Food Timing | Food Timing **`+ — Habit 11 +`** |
| Ch24 | Sugar & Food Sensitivities | Sugar & Food Sensitivities **`+ — Habit 12 +`** |

**Decision needed:** title format — `— Habit 1:`, `(Habit 1)`, or a subtitle line under the chapter heading?

---

### A3. Phases: dividers only, not counted in prose  **[✅ RESOLVED — dividers kept as-is]**
**Reason:** 6 phases are kept as section breaks (ToC + visual dividers like `# Phase 1 – get set up`), but no longer named/enumerated or counted in running text. The only place prose enumerates them is Ch9 — handled in B1.

**Decision (2026-06-08):** keep all 6 `# Phase N – …` divider headings exactly as written, names included. No edits to the phase headings. The prose enumeration removal is carried by **B1** (Ch9) and is the only file change this point requires — so A3 is complete once B1 is applied.
Divider locations (for reference): Ch9 (Phase 1), Ch12 (Phase 2), Ch15 (Phase 3), Ch17 (Phase 4), Ch19 (Phase 5), Ch21 (Phase 6).

---

## B. Ch9 — the structural rewrite  **[✅ APPLIED — audit/ch09-proposed.md; setup-framing omitted per request]**
**Reason:** Ch9 is the lynchpin. It currently names the 3 categories, lists all 6 phases, and gives the "16 habits / 6 phases" count — all three framings we're removing. It needs to become: A/C as the gateway → 3 chapters of setup → 12 habits one at a time.

### B1. Remove the 3-categories + 6-phase enumeration; install the A/C gateway
Current (`audit/ch09-proposed.md`, lines 9–27):

> ~~To break it down, I decided these executives needed training in three key categories:~~
>
> ~~Body clock, nervous system, and removing disrupters.~~
>
> ~~I knew training all three at once was not realistic. So, I built habits that aligned with each category, gradually across six phases.~~
>
> ~~Phase 1: Get set up — the tools and environment that make everything else easier.~~
> ~~Phase 2: Clear the disrupters — the things most likely to be quietly wrecking your sleep right now.~~
> ~~Phase 3: Build your daily rhythm — morning and evening, so the system has a structure to run on.~~
> ~~Phase 4: Train your nervous system — just two habits, but don't underestimate them.~~
> ~~Phase 5: Direct your energy — focus it where it actually moves the needle.~~
> ~~Phase 6: What goes in — what you're putting into your body, and when.~~
>
> ~~The result was 16 habits across these six phases. Ready for you to work through in order, at your own pace. Slow is fast, if it means it sticks.~~

Proposed replacement *(this is the gateway — where the model from the design note is stated in full)*:

> **`+ For most of my life I'd been stuck on the activating setting — wound up, switched on, a system that never clocked off. What was missing was the other one: a calming system strong enough to take over at night. +`**
>
> **`+ Your nervous system runs on those two settings, and they're built to take turns — activating through the day, calming at night. Bad sleep is almost always a fault in that handover. Either the calming system has grown too weak to take over, or the two are swapping on the wrong schedule. +`**
>
> **`+ So the habits do three jobs. Some build the calming system. Some stop you propping up the activating system when you shouldn't. And some keep your clock accurate, so the swap lands on time. Strictly, your body clock is a separate system from your nervous system — but it's close enough to picture three jobs: wind down, stop winding up, keep time. Every habit ahead is one of those three. Once you can see which, you'll know why it's there — and you'll be able to weigh up any new tip someone throws at you. +`**
>
> **`+ The program runs in order — the habits introduced one or two at a time, each building on the last. Twelve habits. Ready for you to work through at your own pace. Slow is fast, if it means it sticks. +`**

*Applied version omits the setup-framing paragraph (decision: setup chapters land fine without pre-framing). B2 decision about "three chapters of setup" is therefore moot.*

### B2. Part 4 header text — same removal
Current (`audit/ch09-proposed.md`, line 59):

> Everything that follows in Part 4 of this book is based on ~~training habits in the three key categories: train your body clock, train your nervous system, and remove disruption. The six phases are how you build them — one habit at a time.~~ **`+ those three jobs: building the calming system, stopping what keeps you activated late, and keeping your clock on time. The habits come one at a time. +`**

**Decision needed:** B1 still mentions setup as "three chapters." If you'd rather the setup chapters stay completely unframed, I can cut that clause.

---

## C. Activating/Calming introduction sequence (Ch4 → Ch8)  **[NEW DRAFT]**
**Reason:** This is the Tier-1 through-line, and it currently doesn't exist before Ch18 — the A/C vocabulary appears nowhere in Ch4–Ch7. These are *additions* that seed the concept early so Ch18 can extend it rather than introduce it. All net-new prose — review voice carefully.

### C1. Ch4 end — label-free idea seed (no naming; names wait for Ch5)  **[✅ APPLIED — new audit/ch04-proposed.md]**
**Reason:** Seeds the two-states-that-trade-off rhythm — including the timing dimension Ch9 needs — **without coining a term**. Two deliberate constraints from the 2026-06-08 design discussion:
- *No collision.* Framed as sitting *underneath* the four executives, so it doesn't fuse with Ch4's own Wake/Sleep Executive split (a different two-way cut) or front-run the autonomic mechanism, which isn't built until cortisol (Ch7) / meditation (Ch18). The **name** (activating/calming) is therefore held back to Ch5, where it lands experientially on caffeine.
- *No second vocabulary.* "Wind up / wind down" is used here as **plain description only**. It is not a concept to be replaced — it becomes the permanent everyday gloss that travels alongside "activating/calming" (named in C2) everywhere after.

Insert after `book/ch04.md` line 93 ("All it needs is clear messaging, across the full twenty-four hours."):

> All it needs is clear messaging, across the full twenty-four hours.
>
> **`+ Underneath all four executives sits one simple rhythm. Through the day the whole system is built to wind up — switched on, ready to act. Through the evening it's meant to wind down — settling, recovering, making room for sleep. The two trade off, day and night. When that trade-off stops happening, sleep is the first thing to break. Hold onto that; it's the thread running through everything ahead. +`**

### C2. Ch5 — first formal use of the terms, attached to caffeine  **[✅ APPLIED — audit/ch05-proposed.md]**
**Reason:** Name the two settings here, hung on caffeine (a behaviour/input), not on adenosine.
Insert after `audit/ch05-proposed.md` line 58 ("The exit isn't willpower. It's understanding what the thing you're reaching for is actually doing."):

> The exit isn't willpower. It's understanding what the thing you're reaching for is actually doing.
>
> **`+ Caffeine is the clearest example of that wind-up from the last chapter. Every cup nudges you toward alert. From here those two settings get their names: activating — the one caffeine feeds — and calming, the one sleep depends on. Caffeine activates you, and not just for an hour. It keeps activating you into the evening, when the night needs the opposite: calm. +`**

### C3. Ch6 — light append at the hyperarousal moment  **[✅ APPLIED — audit/ch06-proposed.md]**
**Reason:** Reinforce the terms where melatonin loses to a hot nervous system.
`audit/ch06-proposed.md` line 40:

> Stress and hyperarousal. Even when melatonin is present and rising on schedule, a nervous system running too hot can override it. The signal is there. But if the mind is still running — thoughts looping, stuck in go-mode **`+ — still activating when it should be calming +`** — melatonin can't win that contest. That's cortisol's problem, and it has a chapter of its own.

### C4. Ch7 — append at the cortisol/melatonin handover (strongest fit)  **[✅ APPLIED — audit/ch07-proposed.md]**
**Reason:** Cortisol *is* the activating chemistry — the cleanest place to cement the through-line.
`audit/ch07-proposed.md`, after line 36:

> Cortisol and melatonin should work in opposition — in the evening as cortisol falls, melatonin rises. When that handover happens cleanly, sleep follows. When the Cortisol executive refuses to pack up and go home, you lie in bed with your eyes open, exhausted and alert, wondering what's wrong with you.
>
> **`+ This is activating and calming at their clearest. Cortisol is the activating chemistry — while it stays high, calming can't take over for the night. Everything in the program is, one way or another, about getting that handover to happen. +`**

### C5. Ch8 — append + dissolve "calm-good / curious-good" (see also E1)  **[✅ APPLIED — audit/ch08-proposed.md; covers E1]**
**Reason:** Replace the one-off "calm-good vs curious-good" framing with the A/C vocabulary.
`audit/ch08-proposed.md` line 43:

> When I switched to more 'wholesome' content, it felt more calming. ~~But feeling curious-good is not the same as feeling calm-good. One is a system winding down. The other has found something worth pursuing — *this is interesting, I want to know more* — and has no intention of stopping.~~ **`+ But it wasn't. Curiosity still activates you — the mind leaning forward, *this is interesting, I want to know more*, with no intention of stopping. Genuine winding down is the calming system taking over. The content felt different; you were in the same gear. +`** This is fine during the day, but not when you should be getting off to sleep.

---

## D. Ch18 — fold-ins  **[✅ APPLIED — new audit/ch18-proposed.md]**
**Reason:** Ch18 currently *introduces* Activating/Calming as brand-new named terms and adds a second named framework (top-down/bottom-up). With C1–C5 in place, the reader already owns the A/C vocabulary, so Ch18 should *extend* it — and the extra framework can dissolve into it.

### D1. Stop introducing A/C as new terms — reframe as "the mechanism behind what you've been doing"
Current (`book/ch18.md`, lines 43–47):

> Your nervous system runs in two broad modes.
>
> The first — a sympathetic dominant state, ~~what I'll call your~~ **`+ your +`** activating system. It's often called fight or flight. High alert, cortisol elevated, the body primed and ready. This is go-mode. Work stress, life pressure, keeping you safe, getting you through a busy day.
>
> The second — a parasympathetic dominant state, ~~or what I'll call your~~ **`+ your +`** calming system. It's often referred to as rest and digest. Cortisol dropping, the body doing the maintenance work...

Add a bridging line before the list (replacing "Your nervous system runs in two broad modes."):

> ~~Your nervous system runs in two broad modes.~~ **`+ You already know these two — we've been calling them the activating and calming systems since the start. Here's the biology underneath them. Your nervous system runs in two broad modes. +`**

*Casing on apply: lowercase every "Activating System / Calming System / Calming Nervous System" instance throughout Ch18 (not just the lines shown here), per the copy convention in the design note.*

### D2. Dissolve "top-down / bottom-up" into plain directional language
**Reason:** It's a second named framework doing the same job as A/C. Keep the body-to-brain mechanism; drop the jargon.

Line 73:
> What I'm going to describe is the one I found most effective and easiest to stick with — and the reason I recommend this specific approach rather than others comes down to ~~something called the top-down / bottom-up approach~~ **`+ the direction the signal travels +`**.

Line 75:
> When the activating ~~Nervous~~ system is running the show, signals are flowing ~~top-down —~~ **`+ one way: +`** brain to body, keeping everything on alert.¹ To shift out of that state, you need to reverse the direction. Body to brain...

Line 77:
> Meditation that keeps you in your head — visualisation, affirmations, thinking your way to calm — ~~runs top-down~~ **`+ keeps the signal flowing brain to body +`**. Both have value. But body-based meditation ~~runs bottom-up~~ **`+ runs the other way, body to brain +`**. It interrupts the loop by changing the direction of the signal.

---

## E. "Calm-good vs hyped-good" — remove everywhere it survives  **[✅ APPLIED — E1 via C5 (ch08), E2 in new audit/ch21-proposed.md]**
**Reason:** Folds entirely into A/C vocabulary; no need for a parallel term.

- **Ch8** — handled in **C5** above.

### E2. Ch21 — two instances  **[✅ APPLIED — audit/ch21-proposed.md]**
`book/ch21.md` line 21:
> ~~This is the calm-good versus hyped-good distinction from Chapter 8.~~ **`+ This is the same thing from Chapter 8. +`** Late-night scrolling ~~is hyped-good with both Wake Executives running on full.~~ **`+ runs both Wake Executives on full — activating you hard, exactly when the night needs calm. +`** The brain is being primed for novelty and threat at exactly the moment it needs to be winding down.

`book/ch21.md` line 49:
> I stayed away from near-miss and crash compilations in those categories – the content matters, not just the topic. I was ~~seeking calm-good, not worked up~~ **`+ after things that calmed me, not wound me up +`**.

### E-flag. Ch15 — **[✅ RESOLVED — not a target]**
The change list named Ch15 as a calm-good/hyped-good site, but the framing does not appear anywhere in `book/ch15.md`. Author confirmed (2026-06-08): no change needed since the language isn't there.

---

## F. "3 Categories" — remove as a named concept  **[STILL PRESENT]**
**Reason:** Removed as a reader-facing framework. Ch9 handled in B. The other restatement is in Ch25.

### F-Ch25. Remove the 3-category restatement → recap the **three jobs** instead  **[✅ APPLIED — new audit/ch25-proposed.md]**
**Reason:** Ch25 is the recap surface for the model (per the design note). Swap the old 3-categories restatement for the three habit jobs, in plain A/C language.
`book/ch25.md` line 9:
> What the habits were actually doing, ~~across all six phases, was working on three things: removing what was getting in the way, training your body clock, and training your nervous system.~~ **`+ was the same thing throughout: building the calming system, clearing away what kept you activated late, and keeping your clock on time — so the calming system could take over when it should. +`** Some were clearing obstacles. Others were actively building the conditions sleep depends on. Each one seemed almost too small to matter — light exposure in the morning, a three-hour gap before dinner, a consistent wake time. None of it felt like fixing sleep. That was the point.

---

## G. Fitness Analogy — don't carry it forward into the close  **[⏸ LEFT — author chose to keep it, 2026-06-08]**
**Reason:** Demoted from Tier 1 — kept as a premise-setter in the *early* chapters (Ch2/Ch3, unchanged), not carried forward as a framework. Ch25 still leans on it in the closing.

`book/ch25.md` line 7:
> The program starts from a different idea. You are not trying to fix sleep directly. You are creating the conditions that allow it to happen. ~~Nobody tries to get fit on the night of a race. You build the fitness first, and the performance follows. Sleep works the same way.~~ **`+ You don't force the outcome on the night; you build the conditions over the days before, and the outcome follows. +`** That shift — from chasing the outcome to supporting the system that produces it — is the whole thing.

**Decision needed:** this is a light rhetorical echo, not a named framework — you may want to keep it. Marked optional.

---

## H. Ch10–24 light A/C appends — SCOPE  **[✅ APPLIED — casing sweep ch19/20/23 + 4 touches ch13/14/15/16; optionals left]**

**Headline finding:** the back half is already largely threaded. The executives ("Wake/Sleep Executive") carry the load throughout, and several chapters already use the A/C terms outright — Ch10 ("activated and calm — the names in this book"), Ch19, Ch20, Ch23. So the plan's "light appends Ch10–24" should be *light* indeed: the real task is a small casing sweep + ~4 one-line touches. Over-appending is the main risk — it would turn a through-line the reader is meant to translate themselves into a drumbeat.

**Two separable workstreams:**

**(1) Casing sweep — needed for consistency (do regardless of the optional touches).** Now that Ch18 is lowercased, these chapters still capitalise the terms and must match the convention (lowercase "activating/calming system"):

| Ch | Instances to lowercase |
|----|------------------------|
| Ch19 Napping | "Calming System getting stronger," "another Calming System session," "added another Calming System session" |
| Ch20 Exercise | "Calming System" ×6+ (e.g. "trained Calming System," "My Calming System wasn't strong enough," "trains the Calming System at rest") |
| Ch23 Food timing | "the Calming System taking its turn, the Activating System standing down," "Digestion is the Activating System switched on" |

(Ch10's "activated and calm" is already lowercase — fine.)

**(2) Optional light touches — one sentence each, getting lighter through the program.** Recommended only where they genuinely reinforce; everything else leave alone.

| Ch | Job | Current A/C state | Recommendation |
|----|-----|-------------------|----------------|
| Ch10 Feedback loop | setup | Already names "activated and calm (the names in this book)" re HRV | **Leave** — already does it |
| Ch11 Supplements | setup | "cortisol should be winding down… making the evenings a little calmer" | **Optional, low** — could add "a small head start for the calming system in the evening" |
| Ch12 Environment | de-activate (setup) | light = "mild alertness"; TV = "nervous system should be winding down" | **Optional, low** — could frame light/TV as "things that keep you activated at night" |
| Ch13 Caffeine | de-activate + timing | C2 already names A/C on caffeine in Ch5; Ch13 body has "wired at night" | **Light touch** — one tie-back: caffeine is the clearest activating input; this is your first de-activating move |
| Ch14 Alcohol | de-activate | "from suppressed to aroused" (4am rebound) | **Light touch** — the 4am rebound is the activating side roaring back; alcohol buys calm now, pays in activation later |
| Ch15 Can't-sleep routine | calming (in the moment) | middle-of-night routine, meditation-first | **Light touch** — frame the routine as getting the calming system back in charge (verify exact insertion point on apply) |
| Ch16 Morning routine | regulate + activate-at-right-time | "You are not building a morning habit. You are setting a clock." | **Light touch** — one line: morning light is the activating side, switched on at the right time, and the clock that times the whole swap |
| Ch17 Evening routine | calming + de-activate + regulate | already "emotionally activating," "nothing activating," "tempers the activation" | **Leave / minimal** — already carries it |
| Ch19 Napping | regulate + calming | already "calming system" (casing only) | **Casing only** |
| Ch20 Exercise | activate + calming + regulate | richest A/C illustration already (spike→clear; yoga trains calming in motion) | **Casing only** |
| Ch22 Hydration | regulate / de-activate | "low-level stress state. Cortisol rises… removing an unnecessary stress signal" | **Optional, low** — "a small activating signal you can remove" |
| Ch23 Food timing | regulate + de-activate | already explicit A/C (casing only) | **Casing only** |
| Ch24 Sugar | de-activate + timing | heavy cortisol/2–3am surge language | **Optional, low** — sugar crash = an activating spike at night |

**Recommended minimum set:** the casing sweep (Ch19/20/23) + the four light touches (Ch13, Ch14, Ch15, Ch16). Leave Ch10/Ch17 as-is; treat Ch11/Ch12/Ch22/Ch24 as optional only if a read-through feels thin. This keeps the through-line present without saturating it — the reader is doing the translation by Ch16–17, exactly as planned.

**Decision needed:** (a) do the casing sweep now (recommended, it's consistency)? (b) which of the light touches do you want — all four, the minimum set, or pick? (c) any of the low-priority optionals?

---

## Suggested order to apply
1. **C1–C5** A/C appends (build the vocabulary first)
2. **B / A1** Ch9 rewrite + headline (the anchor everything refers back to)
3. **D** Ch18 fold-ins
4. **E2 / F / G** Ch21, Ch25 clean-ups
5. **A2** chapter-title numbering + ToC (last, once structure is settled)

**Status — all items resolved/applied (2026-06-08):** A1 ✅ · A2 ✅ · A3 ✅ (dividers kept) · B1/B2 ✅ (setup-framing omitted) · C1 ✅ · C2 ✅ · C3 ✅ · C4 ✅ · C5 ✅ · D1 ✅ · D2 ✅ · E1 ✅ (via C5) · E2 ✅ · E-flag ✅ (Ch15 not a target) · F ✅ · G ⏸ left (author kept the fitness echo).
Model locked: two states / three jobs, prose-only, no per-habit tags; "side" not used; lowercase throughout. Proposals live in `/audit/*-proposed.md`; nothing written to `/book/`.
