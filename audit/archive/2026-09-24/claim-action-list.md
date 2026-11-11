# Claim Action List — consolidated, by chapter

Every actionable finding from both sourcing passes (`claim-references.md` HIGH +
`claim-references-MED.md` MED), grouped by chapter and in claim order, so the manuscript can
be worked through top to bottom. Source links: `claim-references-sources.md` /
`claim-references-MED-sources.md`.

`/book/` is read-only — every change is a proposal in `/audit/` or a stated acceptance in the
endnotes. Many items can be **consciously accepted**; where you do, note the reasoning in the
endnote rather than editing the prose.

**Tags:** `[FIX]` factual error / contradiction (address) · `[NUMBER]` figure off or
unsourced · `[SOFTEN]` overstated / contested (hedge or reframe) · `[SOURCE]` citation to firm
up before publishing · `[NOTE]` minor or already-hedged — likely accept, optional endnote.

**Decision (mark each):** `[ ] edit` · `[ ] accept + endnote` · `[ ] accept as-is`

---

## Ch03 — The Uncomfortable Truth
- **Ch03.1 — CBN is a THC breakdown, "more targeted than CBD"** · `[NOTE]`
  - Evidence for CBN as a sleep aid is thin; "more targeted than CBD" is unproven. Book already frames it skeptically as a forum claim. Likely accept as-is.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — "summary plus sources" endnote filed in `endnotes-draft.md`; refs verified (da Silva 2025, Bonn-Miller 2024, Saleska 2024).
- **Ch03.14 — poor sleep ↔ serious disease** · `[NOTE]`
  - Well supported (CDC/NINDS). Minor: CDC's list doesn't name "cognitive decline" (NINDS covers it). No real action.
  - Decision: `[ ] edit` `[ ] accept + endnote` `[x] accept as-is` — prose stands; well supported (CDC + NINDS).

## Ch05 — Adenosine
- **Ch05.12 — "alcohol… sedates while suppressing slow-wave sleep"** · `[FIX]` **(major — paired with Ch14.8/14.11)**
  - Best reviews (Gardiner 2024; Ebrahim 2013) show alcohol does **not** suppress slow-wave/deep sleep (Ebrahim: early-night SWS *increases*). Reword to: sedation + REM suppression + second-half fragmentation. Revisit the downstream "deep sleep doesn't clear adenosine" mechanism.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — alcohol bullet **removed** from the Ch05 deep-sleep-disruptor list (miscategorised; covered in Ch14). Full chapter: `/audit/ch05-proposed.md`.
- **Ch05.5 — deep sleep clears adenosine, near zero by morning** · `[NOTE]`
  - Homeostatic model is sound; precise overnight-clearance dynamics are the standard description, not a pinned figure. ~~Accept.~~ **Reopened** after asset review: `why-we-wake-at-2-3am.md` §7 shows the molecular decline is gradual, so "near zero by morning" overstates the data (the robust front-loading is the SWA curve).
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "near zero" → "that pressure has largely lifted"; single-lever line lightly hedged (optional/revertable). `/audit/ch05-proposed.md`.

## Ch06 — Melatonin
- **Ch06.9 — melatonin peaks "around midnight or one"** · `[NUMBER]`
  - Peak timing is highly variable (~midnight–3am, some later). "Midnight or one" is the early edge — defensible but low. Optional: "around midnight to the small hours."
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "won't peak until around midnight or one" → "It peaks and holds high through the middle of the night." Aligns with why-we-wake asset (acrophase ~2-4am, wake-time-anchored, Burgess & Fogg 2008) + Ch07.17 ("eases from ~2am"). `/audit/ch06-proposed.md`.
- **Ch06.18 — OTC doses far exceed natural production** · `[NOTE]`
  - Direction correct (low doses suffice). The exact "body makes ~0.3 mg vs OTC 1–10 mg" comparison wasn't pinned. Accept or add a source if you want the number.
  - Decision: `[ ] edit` `[ ] accept + endnote` `[x] accept as-is` — prose states no specific figure; SHF supports the direction. No change.
- **Ch06.19 — high doses extend, blunt sensitivity, grogginess** · `[SOURCE]`
  - "More isn't more" supported; the next-morning grogginess + sensitivity-blunting specifics would benefit from a stronger verbatim.
  - Decision: `[ ] edit` `[ ] accept + endnote` `[x] accept as-is` — **now sourced** (search done): desensitisation clause → Gerdin 2004 (FASEB J, MT2 desensitisation; supraphysiological doses desensitise longer; animal/cell caveat); "more isn't more"/grogginess → Menczel Schrire 2022 (J Pineal Res) + SHF. Citations logged to sources + endnotes. Prose unchanged.

## Ch07 — Cortisol
- **Ch07.7 — cortisol rising "before you open your eyes" = the CAR** · `[FIX]` (mislabel)
  - The cortisol *awakening response* is the surge *after* waking (peaks ~30–45 min later), on top of the overnight circadian rise. Suggest: cortisol rises through late night (circadian), then surges further after waking (the CAR).
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — CAR term dropped (adds no weight, never recurs); pre-waking rise + "peaks in the first hour" kept (already correct). `/audit/ch07-proposed.md`.

## Ch08 — Dopamine
- **Ch08.6 / 08.10 / 08.12 — "fast dopamine recalibrates/desensitises the reward system"** · `[SOFTEN]` **(contested)**
  - Popular idea, but no strong systematic review establishes "screens desensitise the reward system." Soften to a hypothesis ("may," "some evidence suggests").
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — desensitisation claim hedged at both loci (line 21 "may start to lose out"; line 37 "the thinking goes, this may recalibrate… "). Line 33 (novelty/unpredictability) left as-is (supported mechanism). In-prose concession sentence rejected as off-register → moved to endnote with directional evidence (reduced striatal D2 availability in heavy users; "Engineered highs," Addict Behav 2023). `/audit/ch08-proposed.md` + `endnotes-draft.md`.
- **Ch08.14 — passive predictable TV genuinely different** · `[NOTE]`
  - Reasonable extension from novelty/variable-reward; no direct head-to-head. Accept.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose stands; endnote flags it as a directional inference from the dopamine "wanting"/variable-reward mechanism (Berridge 2007; "Engineered highs," Addict Behav 2023), no head-to-head study. `endnotes-draft.md`.

## Ch10 — Your Feedback Loop
- **Ch10.15 — "REM is where memory consolidation happens"** · `[SOFTEN]`
  - Memory consolidation needs **both** non-REM and REM. Consider "REM is central to memory and emotional processing" rather than "where it happens."
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "is where memory consolidation and emotional processing happen" → "is central to memory consolidation and emotional processing" (NINDS: memory needs both non-REM and REM). `/audit/ch11-proposed.md`.
- **Ch10.16 — HRV "reflects how well your nervous system is balancing its two modes"** · `[SOFTEN]`
  - "Higher HRV ~ better recovery" is sound; the two-modes / LF-HF gloss oversimplifies (Shaffer 2017). Minor reword if you want precision.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose stands (already hedged); endnote concedes the two-modes picture is a simplification but "close enough to see how habits move it" (Shaffer & Ginsberg 2017). `endnotes-draft.md`.
- **Ch10.21 — Oura has the most published research** · `[NOTE]`
  - Supported, but many studies are Oura-funded. Book already hedges ("might just mean it publishes most"). Accept.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose stands; reference endnote attaches validation citations (Oura Gen3 PSG, Sleep Med 2024; Sensors 2024). `endnotes-draft.md`.

## Ch11 — Supplements
- **Ch11.7 — PS: soy/sunflower, 300–500 mg, before bed** · `[SOURCE]`
  - Cortisol-blunting trial used 800 mg (brain-cortex PS) under exercise stress; the 300–500 mg soy/sunflower "before bed" dose/timing is weaker/different. Consider softening the dose-timing confidence.
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — dose "300–500 mg" → "around 400 mg"; "The science says take 30–60 min before bed" → "taken 30–60 min before bed". Endnote records Monteleone 1992 (400–800 mg brain-cortex PS, exercise-stress cortisol, not evening). Table PS row → ~400 mg. `/audit/ch12-proposed.md` + `endnotes-draft.md`.
- **Ch11.10 — Magnesium L-threonate "absorbed more effectively, better evidence base for sleep"** · `[SOFTEN]` (overstated)
  - Absorption edge rests on animal data; "better evidence base for sleep" than other forms isn't established (overall Mg-sleep evidence is low quality). Soften.
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — "absorbed more effectively and has a better evidence base for sleep benefits" → "often recommended on the basis that it crosses into the brain more readily". Animal-data / thin-human-evidence caveat moved to endnote (Mah & Pitre 2021), per author. `/audit/ch12-proposed.md` + `endnotes-draft.md`.
- **Ch11.11 — magnesium 150–300 mg in the evening** · `[NOTE]` → upgraded to `[NUMBER]`/clarity
  - Within the broadly "supported" range but on low-quality evidence. Accept or note the evidence caveat.
  - **Web-verified 2026-06-23:** L-threonate is dosed by *compound*, not elemental — standard serving is ~2 g compound (Magtein), delivering only ~144 mg elemental Mg (≈7–8%), usually split across the day. So "150–300 mg, taken in the evening" is ambiguous/misleading depending on read. (User's own brand: 2 g L-threonate → 144 mg elemental.)
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — replaced with form-specific dosing: L-threonate ~2 g compound (≈144 mg elemental, often split); citrate/glycinate ~150–300 mg elemental in the evening. Endnote explains elemental-vs-compound with sources (Magtein dosing; Sports Research label). Table Magnesium row updated to match. `/audit/ch12-proposed.md` + `endnotes-draft.md`.

## Ch12 — Your Sleep Environment
- **Ch12.9 — temperature "the environmental factor with the most direct connection to quality"** · `[SOFTEN]`
  - The effect is real (Okamoto-Mizuno); the superlative "most direct" is author framing, not a ranked finding. Soften or own it as opinion.
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — Option A: "the environmental factor with the most direct connection to sleep quality" → "wired into the biology of sleep itself — your body has to cool down to fall asleep and to stay there". Reframes ranking → mechanism. Endnote quotes Okamoto-Mizuno 2012 (heat/cold → ↑wakefulness, ↓REM, ↓SWS). `/audit/ch13-proposed.md` + `endnotes-draft.md`.
- **Ch12.10 — optimal range 16–26 °C** · `[NOTE]`
  - Book already frames this as a "popular sources" claim. Accept as-is.
  - Decision: `[ ] edit` `[ ] accept + endnote` `[x] accept as-is` — already framed/hedged as "popular sources"; no change.
- **Ch12.11 — core temperature drops "one to two degrees"** · `[NUMBER]` (unit/magnitude)
  - Usual figure ≈ 0.5–1 °C (≈1–2 °F). Read as Celsius this is ~double. Clarify unit, or "about half a degree to a degree (Celsius)."
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "around one to two degrees" → "around half a degree to a degree Celsius (about one to two degrees Fahrenheit)". Shows both units; corrects the °C magnitude. `/audit/ch13-proposed.md`.

## Ch13 — Caffeine
- **Ch13.6 / 13.7 — caffeine "six-hour half-life"** · `[NUMBER]` (high)
  - EFSA (2015) and a 2026 PK study put it ~4 h (range 3–5 h). Use "about four to five hours," or reframe ("effects last well into the evening"). Halving illustration still works directionally.
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — "six-hour" → "roughly five-hour" half-life; "gone in twelve hours / clear by 10pm" → "ten hours / 8pm"; worked example retimed 10am→3pm→8pm. Endnote with EFSA 2015 / Agboola 2026 / SHF. `/audit/ch14-proposed.md` + `endnotes-draft.md`.
- **Ch13.8 / 13.9 — delay first coffee 60–90 min (competes with cortisol/adenosine)** · `[SOFTEN]` (weak/popular)
  - Widely promoted but the morning cortisol-caffeine evidence is thin; book already concedes no tracker sign. Present as a reasonable, low-confidence tip rather than established science.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose stands (already hedged: "appears to train," + "can't point to a sign on my tracker yet"); endnote states plainly it's popular/low-confidence advice, not established science. `endnotes-draft.md`.

## Ch14 — Alcohol
- **Ch14.2 — "zero alcohol is the recommended position"** · `[SOFTEN]` (mixed)
  - For *sleep*, authoritative bodies recommend limiting + timing, not a flat zero (the "no safe level" line is general health). Consider "less is better — ideally none, and never close to bedtime."
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — reframed: "zero" attributed to overall-health (WHO 2023), sleep guidance = less/timing. `/audit/ch15-proposed.md`.
- **Ch14.8 — "suppresses REM and fragments deep sleep"** · `[FIX]` **(major — see Ch05.12)**
  - REM suppression strongly supported; "fragments deep sleep" is not. Reword to REM + second-half fragmentation.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "fragments deep sleep" removed; REM suppression kept, deep sleep noted as preserved/front-loaded. `/audit/ch15-proposed.md`.
- **Ch14.9 — "one or two drinks reduce restorative sleep by ~15 min"** · `[NUMBER]`
  - Dose-response is sourced (Gardiner); the exact 15-min figure isn't in the abstract. Verify against full-text effect sizes, or soften to "measurably cut restorative (REM) sleep."
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — 15-min figure removed; softened to qualitative dose-response (full-text chase offered, not done). `/audit/ch15-proposed.md`.
- **Ch14.10 — "three or four drinks, forty minutes or more"** · `[NUMBER]`
  - Same as Ch14.9 — structure sourced, exact 40-min figure not pinned. Verify or soften.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — 40-min figure removed; folded into the same qualitative dose-response. `/audit/ch15-proposed.md`.
- **Ch14.11 — "fragmented deep sleep leaves adenosine uncleared"** · `[FIX]` **(major — depends on the contradicted deep-sleep claim)**
  - Built on the unsupported "alcohol fragments deep sleep." Rework alongside Ch05.12 / Ch14.8.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — adenosine-clearance hangover mechanism replaced with continuity/REM/autonomic non-recovery. `/audit/ch15-proposed.md`.

## Ch15 — Can't-sleep routine
- **Ch15.21 — "below 17 lux, melatonin suppression is minimal"** · `[FIX]` (number unsupported — proposal already drafted)
  - "17 lux" isn't supported; suppression thresholds vary hugely by person (~6–350 lux). Apply the existing rewrite in `/audit/ch16-light-lux-proposal.md`.
  - Decision: `[ ] edit` `[ ] accept + endnote` `[ ] accept as-is` — **DONE.** Footnote reworded: "17 lux/minimal-below-X" removed → typical ~25 lux (Phillips 2019, ED50 24.6), most sensitive 6–10 lux; + Bauducco ~10-min + Hartstein NSF consensus. `/audit/ch16-proposed.md`.
- **Ch15.22 — "TV ~5 lux vs phone 25–50 lux"** · `[SOURCE]` (no source found)
  - Illustrative/derived figures, not pinned to a measured source. Present as a rough illustration, or find a citable measurement.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — numbers KEPT (author's call) but reframed structurally ("even the most sensitive unlikely affected by a TV"); remain illustrative of the distance principle, not a measured source. `/audit/ch16-proposed.md`.

## Ch16 — Morning Routine
- **Ch16.11 — movement "amplifies the light signal"** · `[NOTE]` (weak extension)
  - Exercise has modest phase-shifting effects; "amplifies the light signal" specifically is an extension. Keep modest.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "But movement alongside it amplifies the signal." → "But movement alongside it helps too — exercise is its own gentle cue to the body clock." Drops the unprovable additive "amplifies the light signal" claim; reframes movement as a modest independent circadian cue (MOV1, T4). `/audit/ch17-proposed.md`.

## Ch18 — Meditation
- **Ch18.21 — "a trained vagus suppresses the cortisol response"** · `[SOURCE]` (extension)
  - Breathing→vagal-tone is solid; the trained-vagus→lower-cortisol step is plausible but not directly demonstrated. State the inferential step or soften.
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — one-word edit: "suppresses" → "helps turn down" the cortisol response. Endnote ⟦EN:Ch18.21⟧ concedes the trained-vagus→lower-cortisol step is a reasonable inference, not directly demonstrated (Russo 2017). `/audit/ch19-proposed.md` + `endnotes-draft.md`.
- **Ch18.28 — nasal breathing naturally slows the breath** · `[SOURCE]`
  - Physiologically sound; firm up a clean source.
  - Decision: `[ ] edit` `[ ] accept + endnote` `[x] accept as-is` — basic respiratory physiology, correctly stated; no reader-facing change, no endnote.
- **Ch18.32 — 528 Hz cue** · `[NOTE]`
  - Conditioning principle is sound; the "528 Hz frequency itself aids sleep" claim is unsupported — but the book already hedges it. Accept.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose unchanged (already hedged); endnote ⟦EN:Ch18.32⟧ adds the one real study (Akimoto 2018, n=9, 528 Hz ↓cortisol/↑oxytocin vs 440 Hz) with an honest credibility caveat (tiny sample, single session, minor journal, unreplicated). `/audit/ch19-proposed.md` + `endnotes-draft.md`.

## Ch19 — Napping
- **Ch19.5 — "don't nap within 7–8 h of bedtime"** · `[NUMBER]` (unsourced)
  - The short-nap (~20 min) part is supported (SHF). The "7–8 h before bedtime" figure wasn't found at an authoritative source — soften or source it.
  - **Web-verified 2026-06-23:** figure IS supported — flagged unsourced only because the first pass checked SHF (AU, silent on timing). Sleep Foundation (US) states "at least 8 hours before bedtime" + "avoid naps after 3 p.m."; Mayo Clinic agrees. Book's "seven to eight" matches.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose stands; reference endnote ⟦EN:Ch19.5⟧ attaches Sleep Foundation (US) + Mayo Clinic. `endnotes-draft.md`.

## Ch20 — Exercise
- **Ch20.17 — morning exercise "linked to lower baseline cortisol"** · `[NOTE]`
  - Supported that regular activity lowers cortisol/improves sleep, but not morning-specific or "baseline"-specific. Keep general.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — two deletions, no additions: "regular morning exercise to lower baseline cortisol" → "regular exercise to lower cortisol". De Nys 2022 isn't morning- or baseline-specific; morning-timing logic earlier in the para is untouched (rests on the cortisol-curve mechanism). `/audit/ch21-proposed.md`.
- **Ch20.18 — research: finish vigorous exercise 4 h before bed** · `[SOFTEN]` (mixed/contradicts)
  - Evidence (Stutz 2019) supports ~1 h for most; 4 h is overstated. Book already adds the healthy-sleeper caveat — lean on that.
  - **Web-verified 2026-06-23 — flag WITHDRAWN.** The 4 h figure is directly supported by Leota et al. 2025 (*Nat Commun*; 14,689 adults / 4.08M person-nights WHOOP data): "exercise bouts ending ≥4 hours before sleep onset are not associated with changes in sleep." Stutz 2019 (≤1 h harm for healthy sleepers) is now the nuance, not the headline.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose stands; reference endnote ⟦EN:Ch20.18⟧ attaches Leota 2025 (primary, 4 h) + Stutz 2019 (nuance). Verbatim pinned via Europe PMC. `endnotes-draft.md` + reference files updated.
- **Ch20.19 — his safer margin: 6 h before bed** · `[NOTE]` (author self-experiment)
  - Beyond the evidence (research ~1 h). Keep clearly framed as personal caution, not "the research says."
  - Decision: `[ ] edit` `[ ] accept + endnote` `[x] accept as-is` — already framed as self-experimentation; now sits just beyond a solid 4 h research floor (Leota 2025), reading as sensible caution. No change.

## Ch22 — Hydration
- **Ch22.4 — mild dehydration raises cortisol** · `[NOTE]`
  - Supported, but strongest evidence is exercise/heat dehydration; "mild everyday dehydration" is a softer extension. Optional caveat.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — prose already modest; no change. Endnote ⟦EN:Ch22.4⟧ concedes the firmest evidence is exercise/heat dehydration, everyday version a reasonable extension (Zaplatosch & Adams 2020). `endnotes-draft.md`.
- **Ch22.7 / 22.8 — elevated cortisol → loud bladder signal / night-holding needs low cortisol** · `[NOTE]` (author mechanism)
  - Nocturia is real (overnight vasopressin); the specific cortisol→nocturia link is the author's mechanism, not directly demonstrated. Note as such.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — no prose change. Endnote ⟦EN:Ch22.7-8⟧ flags the sleep-depth→bladder-awareness link as well grounded (vasopressin + arousal), the cortisol→bladder step as the author's own inference. `endnotes-draft.md`.
- **Ch22.12 — "two to three litres a day"** · `[NUMBER]` (high)
  - EFSA adequate intake is 2.0 L (women) / 2.5 L (men) total water (~1.5–2 L as fluids). The "3 L" upper bound slightly overstates it.
  - Decision: `[x] edit` `[ ] accept + endnote` `[ ] accept as-is` — "somewhere between two and three litres is a reasonable daily amount" → "around two litres is usually a reasonable daily amount — a little more if you're active or it's hot". Brings the 3 L top end to the EFSA figure; names the legitimate reason intake rises; aligns with the two-litre bottle. `/audit/ch23-proposed.md`.

## Ch23 — Food Timing
- **Ch23.13a — "protein steadies blood sugar overnight"** · `[SOFTEN]` (mixed)
  - Plausible and standard advice for glucose problems, but controlled trials are mixed on macronutrient type in healthy people. Soften to "may help."
  - **Web-verified 2026-06-23:** no reputable body picks protein over carbs — Sleep Foundation & Northwestern Medicine recommend a carb+protein *combination*, and attribute blood-sugar stability to complex carbs (protein on the tryptophan side). Validates "both have a case."
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — one-word soften: "Protein steadies blood sugar overnight" → "Protein may help steady blood sugar overnight". Endnote ⟦EN:Ch23.13a⟧ adds the combination guidance (Sleep Foundation, Northwestern Medicine) + the healthy-vs-glucose-problem nuance. carb→tryptophan half (13b) unchanged. `/audit/ch24-proposed.md` + `endnotes-draft.md`.

## Ch24 — Sugar & Food Sensitivities
- **Ch24.11 — sugar crash → reactive hypoglycaemia → 2–3am waking** · `[NOTE]` (extension)
  - Reactive hypoglycaemia is established; applying it to normal evening sugar and the 2–3am waking is a reasonable extrapolation, not a demonstrated chain. Note the inferential step.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — no prose change; covered by ONE shared endnote with 24.16/17 (single mechanism). See below.
- **Ch24.16 / 24.17 — evening sugar disrupts handover / triggers 2–3am waking** · `[NOTE]` (extension)
  - Each link sourced; the full nocturnal-sugar→waking chain is extrapolation. Note as above.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — no prose change (¶40 already hedges well). ONE shared endnote ⟦EN:Ch24.11-16-17⟧ at ¶40 concedes the chain is a well-reasoned mechanism built from established parts (reactive hypoglycaemia + cortisol counter-regulation + 2am handover), not a directly demonstrated cause. `/audit/ch25-proposed.md` + `endnotes-draft.md`.
- **Ch24.20 — food sensitivities cause a "low-grade immune response"** · `[SOFTEN]` (contested mechanism)
  - Non-IgE intolerances exist, but the immune-response mechanism is debated. Keep tentative.
  - **Web-verified 2026-06-23:** part-evidenced, part-contested. Non-IgE immune-mediated food disorders are real & diet→low-grade inflammation is established, BUT the individual-sensitivity→background-immune-response framing rests on food-specific IgG (also a normal exposure marker; no validated test) — same territory the book's own 24.24 calls contested.
  - Decision: `[x] edit` `[x] accept + endnote` `[ ] accept as-is` — hedge: "generating a low-grade immune response" → "generating what may be a low-grade immune response". Reconciles ¶52 with ¶58. Summary-plus-sources endnote ⟦EN:Ch24.20⟧ (non-IgE review PMC8625578; diet/low-grade-inflammation Calder 2015). `/audit/ch25-proposed.md` + `endnotes-draft.md`.
- **Ch24.21 — symptoms: congestion, fog, fatigue, bloating** · `[SOURCE]`
  - Plausible but nonspecific; firm up a source before publishing.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — no prose change. Reference endnote ⟦EN:Ch24.21⟧ (NHS food intolerance; brain-fog/diet/GI study PMC11857395) with honest "symptoms real but nonspecific — investigate, don't diagnose; rule out coeliac first" caveat. `endnotes-draft.md`.
- **Ch24.22 — common culprits: gluten, dairy, eggs, soy** · `[SOURCE]`
  - Consistent with major-allergen lists (FDA), but the exact four-food ranking wasn't pinned. Add a clean source.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — no prose change. Reference endnote ⟦EN:Ch24.22⟧: all four (wheat/milk/egg/soy) are FDA major allergens; "most common" framed as illustrative shortlist, not a pinned ranking. `endnotes-draft.md`.
- **Ch24.24 — reactivity blood tests contested, not diagnostic** · `[NOTE]`
  - Strongly supported (EAACI/AAAAI) and already hedged by the book. Accept — no change needed.
  - Decision: `[ ] edit` `[x] accept + endnote` `[ ] accept as-is` — no prose change; reference endnote ⟦EN:Ch24.24⟧ attaches EAACI (Stapel 2008, "should not be performed") + AAAAI, which strongly back the book's skepticism. `endnotes-draft.md`.

---

## Priority summary

- **Must-fix (factual):** Ch05.12 / Ch14.8 / Ch14.11 (alcohol & deep sleep — one coordinated rewrite); Ch07.7 (CAR mislabel); Ch15.21 (17 lux — proposal already drafted).
- **Numbers to correct or verify:** Ch12.11 (temp drop unit), Ch13.6 (caffeine half-life), Ch14.9 / 14.10 (alcohol minutes), Ch22.12 (water litres), Ch19.5 (nap 7–8 h), Ch06.9 (melatonin peak).
- **Soften / reframe:** Ch08.6–12 (dopamine), Ch10.15 (REM/memory), Ch10.16 (HRV), Ch11.10 (Mg L-threonate), Ch12.9 (temp superlative), Ch13.8–9 (first coffee), Ch14.2 (zero alcohol), Ch20.18 (4 h exercise), Ch23.13a (protein), Ch24.20 (food-sensitivity immune claim).
- **Sources to firm up:** Ch06.19, Ch11.7, Ch15.22, Ch18.21, Ch18.28, Ch24.21, Ch24.22.
- **Likely accept (already sound / hedged):** Ch03.1, Ch03.14, Ch05.5, Ch06.18, Ch10.21, Ch11.11, Ch12.10, Ch16.11, Ch18.32, Ch20.17, Ch20.19, Ch22.4, Ch22.7–8, Ch24.11, Ch24.16–17, Ch24.24.
