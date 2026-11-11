# HIGH Claims — Expansion, De-dupe & Grouping (Step 1 scaffold)

Working file for the blind-endnotes project. This is **Step 1 only**: each of the 61 HIGH
claims expanded to a full sentence + the exact source sentence(s) from `/book/`, then
grouped into distinct facts and topic search-clusters. **No searching has happened yet.**
Citations get added in Steps 2–3 and the finished result moves to `claim-references.md`.

Rules being followed: `/book/` read-only (read for context only); never round a number to
fit; split bundled facts; group identical facts and source once.

---

## How the de-dupe shook out

The 61 HIGH claims collapse to **59 distinct facts** across **20 topic clusters**. The
reduction is modest (the author had already curated HIGH down to mostly-distinct claims),
but the *clustering* is where the search efficiency comes from — one authoritative source
typically covers several facts in a cluster (e.g. one melatonin guideline serves all six
melatonin claims).

De-dupe actions taken:
- **Merged** Ch05.12 + Ch14.8 → one fact (alcohol suppresses REM / slow-wave sleep).
- **Merged** Ch13.10 + Ch24.5 → one fact (sleep loss reduces self-control/willpower).
- **Paired** Ch14.9 + Ch14.10 → one dose-response fact (restorative-sleep loss by drink count).
- **Split** Ch23.13 → two facts (protein→overnight glucose; carbs→tryptophan→melatonin).

Net: 61 claims − 3 merges + 1 split = 59 distinct facts.

---

## Cluster 1 — Caffeine (3 facts)

**Ch13.4** [HIGH] — *Caffeine works mainly by blocking the brain's adenosine receptors, masking accumulated sleep pressure rather than adding energy.*
> "It blocks the receptors in your brain that read adenosine — the chemical that builds through the day and pushes you toward sleep. The adenosine is still accumulating; your brain just can't feel it."
Number check: none. Mechanism claim.

**Ch13.6** [HIGH] — *Caffeine has roughly a six-hour half-life (the amount in your system halves every ~6 hours).*
> "I read that it had a six-hour half-life ... Every six hours, the amount in your system halves."
Number check: **6-hour half-life** — must confirm figure (commonly cited 4–6 h; verify).

**Ch07.18** [HIGH] — *Caffeine taken late in the day acts as a mild cortisol stimulus, keeping the evening cortisol baseline higher than it should be.*
> "Every cup taken too late is a mild cortisol stimulus — a small kick to a system that should be gradually falling toward evening."
Number check: none.

## Cluster 2 — Adenosine / deep sleep (2 facts)

**Ch05.5** [HIGH] — *Deep (slow-wave) sleep is when the brain clears adenosine; after a proper night levels return to near zero by morning.*
> "During sleep, particularly deep (slow wave) sleep, the brain clears adenosine." / "By morning, if that clearing has happened properly, levels are back to near zero."
Number check: "near zero" — qualitative.

**Ch05.16** [HIGH] — *Deep sleep is front-loaded into the first part of the night, so a late start can cost you deep-sleep amount.*
> "It's front-loaded into the first part of the night — start late and you may not recover the full amount."
Number check: none.

## Cluster 3 — Melatonin (6 facts)

**Ch06.9** [HIGH] — *Endogenous melatonin peaks around midnight or 1am.*
> "Melatonin itself won't peak until around midnight or one — long after this window."
Number check: **~midnight–1am peak** — verify timing.

**Ch06.12** [HIGH] — *Evening light, especially short-wavelength light from screens, delays or suppresses melatonin.*
> "Bright light in the evening — particularly the short-wavelength light that screens produce — tells the brain it's still daytime. The signal gets delayed, or somewhat suppressed."
Number check: none (lux thresholds handled in Cluster 4).

**Ch06.16** [HIGH] — *Melatonin is genuinely useful for jet lag and shift-work adjustment (shifting the body clock).*
> "Jet lag, or adjusting for shift work, are different. Here, shifting the clock is exactly the point."
Number check: none (dose in Ch06.17).

**Ch06.17** [HIGH] — *For circadian shifting, a small dose of 0.5–1mg taken 30–60 min before the new target bedtime.*
> "A small dose — 0.5 to 1mg — taken 30 to 60 minutes before your new target bedtime helps nudge the clock toward where it needs to be."
Number check: **0.5–1mg; 30–60 min before** — verify both.

**Ch06.18** [HIGH] — *Most over-the-counter melatonin doses far exceed what the body naturally produces.*
> "Most over-the-counter melatonin runs far higher than what the body naturally produces."
Number check: "far higher" — qualitative; look for a quantitative comparison (endogenous output vs typical OTC mg).

**Ch06.19** [HIGH] — *High doses leave residual melatonin circulating into the morning (grogginess), don't increase the effect, and blunt sensitivity to the natural signal.*
> "Take too much, and residual melatonin can still be circulating by morning, producing grogginess ... a high dose doesn't increase the effect — it just extends it into the morning and gradually blunts your sensitivity to the natural signal."
Number check: none.

## Cluster 4 — Light & screens (5 facts)

**Ch15.21** [HIGH] — *Below ~17 lux reaching the eye, melatonin suppression is minimal.*
> "Studies show that below 17 lux, melatonin suppression is minimal."
Number check: **17 lux threshold** — verify exact figure / source.

**Ch15.22** [HIGH] — *A TV at 3m delivers ~5 lux to the eye vs 25–50 lux from a phone at 30cm.*
> "A standard TV at three metres registers around 5 lux by the time the light reaches your eye — compared to 25–50 lux from a phone held 30cm from your face."
Number check: **TV ~5 lux; phone 25–50 lux** — verify both figures (likely weak/derived).

**Ch21.3** [HIGH] — *On-screen content (stimulating/emotional) delays sleep onset more than the screen's light alone.*
> "More recent studies show that what's on the screen plays the bigger role: stimulating or emotionally engaging content delays sleep onset more than light exposure alone."
Number check: none. (Potentially contested — watch for mixed evidence.)

**Ch16.5** [HIGH] — *Morning light is the most powerful cue for setting the circadian clock.*
> "The morning signal is the most powerful cue your body has to set its internal clock."
Number check: none.

**Ch16.8** [HIGH] — *Natural daylight, even overcast, is dramatically brighter than indoor lighting.*
> "Natural light, even on an overcast day, is dramatically brighter than indoor lighting."
Number check: implicit (outdoor vs indoor lux) — find quantitative lux comparison.

## Cluster 5 — Cortisol rhythm (4 facts)

**Ch07.7** [HIGH] — *Cortisol begins rising before waking — the cortisol awakening response.*
> "Before you open your eyes, it's already rising — called the cortisol awakening response."
Number check: none.

**Ch07.8** [HIGH] — *Cortisol peaks in the first hour or so after waking, then declines across the day.*
> "It peaks in the first hour or so after waking, then begins its long downward curve through the day."
Number check: **peak within ~first hour** — verify (CAR peak ~30–45 min post-waking).

**Ch07.17** [HIGH] — *Melatonin holds high early, eases from ~2am; if cortisol is riding high it fills the gap and wakes you.*
> "Melatonin holds high through the first stretch of the night, then from around 2 am it begins to ease ... cortisol jumps right in to fill the gap."
Number check: **~2am** — qualitative timing; verify nocturnal cortisol nadir / rise.

**Ch07.20** [HIGH] — *Sleep deprivation is itself a stressor that raises cortisol.*
> "Sleep deprivation is stress - the body responds just like a threat — by releasing cortisol."
Number check: none.

## Cluster 6 — Alcohol (5 facts)

**Ch05.12 + Ch14.8** [HIGH] (merged) — *Alcohol sedates rather than inducing natural sleep, suppressing REM and fragmenting deep/slow-wave sleep.*
> Ch05.12: "Alcohol feels like a sleep aid, but it sedates you while suppressing slow-wave sleep."
> Ch14.8: "In the first part of the night, alcohol attacks both. It suppresses REM and fragments deep sleep."
Number check: none.

**Ch14.2** [HIGH] — *The recommended position is zero alcohol.*
> "the science here is unambiguous, and rather uncomfortable: zero alcohol is the recommended position."
Number check: none. (Verify whether bodies actually state "zero" for sleep specifically vs general health — possible nuance.)

**Ch14.9 + Ch14.10** [HIGH] (paired dose-response) — *1–2 drinks cut restorative sleep ~15 min; 3–4 drinks ~40 min or more.*
> "Research suggests that just one or two drinks reduces restorative sleep by around fifteen minutes. Three to four drinks, and that figure can rise to forty minutes or more."
Number check: **~15 min (1–2 drinks); ~40 min+ (3–4 drinks)** — verify both figures (likely hard to source exactly).

**Ch14.12** [HIGH] — *Alcohol causes a metabolic rebound (raised HR/BP, shift to activation) that wakes you around 3–4am.*
> "This is metabolic rebound: heart rate up, blood pressure up, the body shifting from suppressed to activated ... Three or four in the morning, heart going."
Number check: **3–4am** — qualitative.

**Ch14.13** [HIGH] — *REM rebound after alcohol brings more intense, vivid, sometimes disturbing dreams in the early hours.*
> "you hit REM rebound. The REM suppressed earlier springs back — often as more intense, vivid, sometimes disturbing dreams in the early hours."
Number check: none.

## Cluster 7 — Temperature (5 facts)

**Ch12.10** [HIGH] — *Commonly quoted optimal bedroom temperature is ~16–26°C.*
> "Most popular sources quote an optimal range of somewhere between 16 and 26 degrees Celsius."
Number check: **16–26°C** — verify (note author frames it as "popular sources").

**Ch12.11** [HIGH] — *Core body temperature drops by ~1–2°C as part of sleep initiation.*
> "Before you fall asleep, your core body temperature begins to drop by around one to two degrees."
Number check: **1–2°C drop** — verify (commonly cited ~1–2°F / ~0.5–1°C — watch unit discrepancy).

**Ch12.13** [HIGH] — *A too-warm room fragments sleep and increases awakenings, especially during REM.*
> "Too warm and it struggles, fragmenting sleep and pushing you toward awakenings. Especially during REM sleep..."
Number check: none.

**Ch12.14** [HIGH] — *During REM the body largely stops regulating its own temperature.*
> "Especially during REM sleep, when your body largely stops regulating its own temperature and is left at the mercy of the room."
Number check: none.

**Ch20.6** [HIGH] — *Intense exercise raises body temperature and it can take 30 min–2h to return to baseline.*
> "Intense exercise raises body temperature significantly, and it can take anywhere from thirty minutes to two hours to return to baseline."
Number check: **30 min–2h** — verify.

## Cluster 8 — Sleep architecture / REM function (1 fact)

**Ch10.15** [HIGH] — *REM sleep is where memory consolidation and emotional processing happen.*
> "REM sleep is where memory consolidation and emotional processing happen."
Number check: none. (Note: Ch10.14 "deep sleep does physical repair" is MED — not in this pass.)

## Cluster 9 — Trackers (2 facts)

**Ch10.11** [HIGH] — *A good sleep-efficiency target is above 85% (time asleep vs time in bed).*
> "What is your sleep efficiency? (time in bed asleep vs awake - good target is above 85%)"
Number check: **>85%** — verify (AASM/standard efficiency norms).

**Ch10.19** [HIGH] — *Consumer-tracker sleep-stage error is ~20–30 min per night, narrowing to ~10 min over a week.*
> "The validation studies I've seen put the nightly error around twenty to thirty minutes, narrowing to roughly ten once you average across a week."
Number check: **20–30 min nightly / ~10 min weekly** — verify against validation studies (likely partial).

## Cluster 10 — Supplements (6 facts)

**Ch11.6** [HIGH] — *Phosphatidylserine appears to blunt the evening cortisol response.*
> "Phosphatidylserine ... appears to blunt the evening cortisol response."
Number check: none (dose in Ch11.7).

**Ch11.7** [HIGH] — *PS: soy- or sunflower-derived, 300–500mg, taken 30–60 min before bed.*
> "The form to look for is soy- or sunflower-derived. The typical dosage is somewhere between 300 and 500 milligrams. The science says take 30 – 60 minutes before bed."
Number check: **300–500mg; 30–60 min before bed** — verify.

**Ch11.8** [HIGH] — *Ashwagandha (KSM-66 extract has the most evidence) reduces the stress response, aiding sleep.*
> "The extract with the most evidence behind it is called KSM-66 ... Its primary effect for sleep is reducing the stress response."
Number check: none (dose in Ch11.9).

**Ch11.9** [HIGH] — *Ashwagandha: 300–600mg, taken late afternoon or evening.*
> "The dosage range is 300 – 600 milligrams. The science says take in the late afternoon or evening."
Number check: **300–600mg** — verify.

**Ch11.10** [HIGH] — *Magnesium L-threonate is absorbed more effectively and has a better evidence base for sleep.*
> "the form worth looking for is Magnesium L-threonate, which is absorbed more effectively and has a better evidence base for sleep benefits."
Number check: none. (Watch: "absorbed more effectively" for brain may be contested — possible mixed/weak.)

**Ch11.11** [HIGH] — *Magnesium: ~150–300mg, taken in the evening.*
> "The dosage is around 150 – 300 milligrams, taken in the evening."
Number check: **150–300mg** — verify.

## Cluster 11 — Sleep loss & self-control (1 fact)

**Ch13.10 + Ch24.5** [HIGH] (merged) — *Sleep deprivation measurably reduces the capacity for self-control / willpower.*
> Ch13.10: "Sleep deprivation measurably reduces your capacity for self-control."
> Ch24.5: "sleep deprivation measurably reduces your capacity for self-control — willpower runs on a battery that poor sleep never fully recharges."
Number check: none.

## Cluster 12 — Appetite hormones (3 facts)

**Ch24.6** [HIGH] — *Poor/insufficient sleep raises ghrelin and lowers leptin.*
> "Lack of sleep also pulls two of the appetite managers out of line. It raises ghrelin ... and lowers leptin."
Number check: none.

**Ch24.7** [HIGH] — *Ghrelin acts on the reward system, tilting cravings toward sweet, fatty food.*
> "ghrelin doesn't only make you hungry — it acts on the brain's reward system, tilting what you crave specifically toward sweet, fatty food."
Number check: none. (Possible inferential gap — verify ghrelin→reward→food-type vs general sleep-loss craving data.)

**Ch24.11** [HIGH] — *After a large/refined sugar load, insulin correction overshoots and glucose drops below where it started.*
> "If the sugar load is large, or if this is happening repeatedly across the day, the correction overshoots. Glucose drops below where it started."
Number check: none (reactive hypoglycaemia — verify it's an established phenomenon).

## Cluster 13 — Vagus nerve / breathing (3 facts)

**Ch18.18** [HIGH] — *A slow exhale mechanically activates the vagus nerve via the diaphragm and lungs.*
> "The slow exhale mechanically activates the vagus nerve through the diaphragm and the lungs."
Number check: none.

**Ch18.21** [HIGH] — *A trained/well-exercised vagus nerve suppresses the cortisol response.*
> "A trained, well-exercised one suppresses the cortisol response."
Number check: none. (Watch for inferential gap — HRV/vagal-tone vs cortisol.)

**Ch18.29** [HIGH] — *Inhaling speeds heart rate; exhaling+pausing slows it, so a longer exhale+pause nets a slowdown.*
> "When you inhale, your heart rate speeds up. When you exhale and pause, it slows down. With the exhale and pause longer than your inhale, there's more time slowing down than speeding up."
Number check: none (respiratory sinus arrhythmia).

## Cluster 14 — CBT-i / ACT-i (2 facts)

**Ch15.16** [HIGH] — *CBT-i makes "don't lie in bed awake; get up" (stimulus control) a central recommendation.*
> "CBT-i — cognitive behavioural therapy for insomnia — makes \"don't lie in bed awake; get up\" a central recommendation."
Number check: none.

**Ch15.17** [HIGH] — *ACT-i adds acceptance of wakefulness, since the struggle generates more arousal than the wakefulness itself.*
> "ACT-i, its acceptance-based cousin, adds the why: acceptance of wakefulness, because the struggle generates more arousal than the wakefulness itself."
Number check: none.

## Cluster 15 — Exercise & sleep (2 facts)

**Ch20.17** [HIGH] — *Regular morning exercise is linked to lower baseline cortisol and better sleep over time.*
> "Studies also link regular morning exercise to lower baseline cortisol levels and better sleep quality over time."
Number check: none. (Possible mixed evidence — verify.)

**Ch20.18** [HIGH] — *Research recommends finishing vigorous exercise at least 4 hours before sleep onset.*
> "The research recommends finishing vigorous exercise at least four hours before sleep onset."
Number check: **≥4h before sleep** — verify (much evidence suggests ~1–2h is sufficient for most; possible discrepancy/mixed).

## Cluster 16 — Bedtime regularity (1 fact)

**Ch17.13** [HIGH] — *Even modest deviations later than usual bedtime show measurable effects on next-day heart rate and recovery.*
> "even modest deviations later than your usual bedtime show measurable effects on heart rate and recovery the following day."
Number check: none (links to "within 30 min" guidance — verify regularity-recovery evidence).

## Cluster 17 — Food timing (3 facts)

**Ch23.7** [HIGH] — *Research is consistent that eating closer to bedtime worsens sleep; ~3-hour gap as a minimum.*
> "The research is consistent on this: the closer to bed you eat, the worse the night. I use 3 hours as the target."
Number check: **3-hour gap** — verify whether evidence specifies a threshold.

**Ch23.13a** [HIGH] (split) — *Protein helps steady blood sugar overnight.*
> "Protein steadies blood sugar overnight"
Number check: none.

**Ch23.13b** [HIGH] (split) — *Carbohydrates help tryptophan reach the brain to support melatonin.*
> "carbohydrates help tryptophan reach the brain to support melatonin."
Number check: none (carb→tryptophan/LNAA ratio→serotonin/melatonin — verify chain).

## Cluster 18 — Menopause / HRT (2 facts)

**Ch04.20** [HIGH] — *In perimenopause/menopause, falling progesterone and oestrogen can sharply worsen sleep (a manager-level disruption).*
> "For some women, sleep deteriorates sharply in perimenopause or menopause as progesterone and oestrogen drop."
Number check: none.

**Ch04.21** [HIGH] — *If menopause is the only change, HRT may be enough to restore the conditions for sleep.*
> "If menopause is the only thing that changed, HRT may be enough to restore the conditions that make sleep possible again."
Number check: none.

## Cluster 19 — Health consequences & drowsy driving (2 facts)

**Ch03.14** [HIGH] — *Poor sleep is linked to serious long-term conditions: heart disease, diabetes, depression, cognitive decline.*
> "Poor sleep is linked to serious, long-term consequences — heart disease, diabetes, depression, cognitive decline."
Number check: none. (Strong T1 candidates — WHO/CDC/NIH.)

**Ch03.15** [HIGH] — *Driving tired can impair you as badly as driving drunk.*
> "And driving tired can impair you as badly as driving drunk."
Number check: implicit (hours-awake vs BAC equivalence) — verify the equivalence claim/figures.

## Cluster 20 — Dehydration & cortisol (1 fact)

**Ch22.4** [HIGH] — *Even mild dehydration registers as low-level stress and raises the cortisol baseline.*
> "Even mild dehydration — the kind you don't consciously notice — is enough for the body to register as a low-level stress state. Cortisol rises in response."
Number check: none. (Possible inferential gap — dehydration→cortisol evidence; verify.)

---

## Grouping summary

| # | Cluster | Distinct facts | Claim IDs |
|---|---------|---------------|-----------|
| 1 | Caffeine | 3 | Ch13.4, Ch13.6, Ch07.18 |
| 2 | Adenosine / deep sleep | 2 | Ch05.5, Ch05.16 |
| 3 | Melatonin | 6 | Ch06.9, Ch06.12, Ch06.16, Ch06.17, Ch06.18, Ch06.19 |
| 4 | Light & screens | 5 | Ch15.21, Ch15.22, Ch21.3, Ch16.5, Ch16.8 |
| 5 | Cortisol rhythm | 4 | Ch07.7, Ch07.8, Ch07.17, Ch07.20 |
| 6 | Alcohol | 5 | Ch05.12+Ch14.8, Ch14.2, Ch14.9+Ch14.10, Ch14.12, Ch14.13 |
| 7 | Temperature | 5 | Ch12.10, Ch12.11, Ch12.13, Ch12.14, Ch20.6 |
| 8 | REM function | 1 | Ch10.15 |
| 9 | Trackers | 2 | Ch10.11, Ch10.19 |
| 10 | Supplements | 6 | Ch11.6, Ch11.7, Ch11.8, Ch11.9, Ch11.10, Ch11.11 |
| 11 | Sleep loss & self-control | 1 | Ch13.10+Ch24.5 |
| 12 | Appetite hormones | 3 | Ch24.6, Ch24.7, Ch24.11 |
| 13 | Vagus / breathing | 3 | Ch18.18, Ch18.21, Ch18.29 |
| 14 | CBT-i / ACT-i | 2 | Ch15.16, Ch15.17 |
| 15 | Exercise & sleep | 2 | Ch20.17, Ch20.18 |
| 16 | Bedtime regularity | 1 | Ch17.13 |
| 17 | Food timing | 3 | Ch23.7, Ch23.13a, Ch23.13b |
| 18 | Menopause / HRT | 2 | Ch04.20, Ch04.21 |
| 19 | Health consequences & driving | 2 | Ch03.14, Ch03.15 |
| 20 | Dehydration & cortisol | 1 | Ch22.4 |
| | **Total** | **59** | **(from 61 claims)** |

## Number/dose checks flagged for verification (must match source figure exactly)

Caffeine 6-h half-life · Melatonin peak ~midnight–1am · Melatonin 0.5–1mg / 30–60 min ·
17 lux threshold · TV ~5 lux vs phone 25–50 lux · Cortisol peak within first hour ·
Alcohol −15 min (1–2 drinks) / −40 min+ (3–4 drinks) · Bedroom 16–26°C · Core temp −1–2° ·
Exercise temp 30 min–2h · Sleep efficiency >85% · Tracker staging error 20–30 min/~10 min ·
PS 300–500mg · Ashwagandha 300–600mg · Magnesium 150–300mg · Exercise ≥4h before bed ·
Food ~3h before bed.

## Watch-list (claims that may end up mixed / weak / contradicted)

- **Ch20.18** finish vigorous exercise ≥4h before — much literature finds ~1–2h adequate; possible discrepancy.
- **Ch21.3** content > light for delaying sleep onset — recent but possibly contested.
- **Ch11.10** Mg L-threonate "absorbed more effectively" for sleep — evidence thin/mostly animal.
- **Ch15.22 / Ch12.10** lux figures and 16–26°C — author flags these as "popular sources"; may only reach T6.
- **Ch22.4** dehydration→cortisol — limited direct human evidence; possible T4 inferential.
- **Ch24.7** ghrelin→sweet/fatty craving specifically — may need T4 extension.

---

---

# STEP 2 RESULTS — T1/T2 authoritative-body sweep

Every quote below was retrieved and read this session from the URL given. Number checks
done against the book's figure. "Resolved" = concept confirmed at T1/T2 (number consistent
or none). "Concept-confirmed, number pending" = body supports the idea but the specific
figure/mechanism still needs T3. Everything else routes to Step 3.

## A. Resolved at T1/T2 (13 facts)

**Ch03.14 — poor sleep → serious disease | Tier T1**
CDC, *Chronic Disease Indicators: Sleep* (2024). https://www.cdc.gov/cdi/indicator-definitions/sleep.html
> "Insufficient sleep duration is associated with an increased risk of a number of chronic conditions—such as obesity, diabetes, hypertension, heart disease, stroke, anxiety, and depression."
Supporting (cognitive decline): NINDS, *Brain Basics: Understanding Sleep*. https://www.ninds.nih.gov/health-information/public-education/brain-basics/brain-basics-understanding-sleep
> "Research shows that a chronic lack of sleep, or getting poor quality sleep, increases the risk of health problems like high blood pressure, cardiovascular disease, diabetes, depression, and obesity."
Number check: NA. Evidence: **supports**. Note: CDC list doesn't name "cognitive decline"; NINDS covers cognition/Alzheimer's separately — book's four-item list is fully supported across the two.

**Ch03.15 — tired driving ≈ drunk driving | Tier T1**
CDC/NIOSH, *Training for Nurses on Shift Work*, Module 3. https://www.cdc.gov/niosh/work-hour-training-for-nurses/longhours/mod3/08.html
> "Being awake for 17 hours is similar to having a BAC of 0.05%." / "Being awake for 24 hours is similar to having a BAC of 0.10%."
> "Several studies show similarities between fatigue-related impairment in cognitive and physiological functioning, and impairments due to alcohol intoxication."
Number check: book gives no figure; equivalence holds (0.10% at 24h is above the 0.08% legal limit). Evidence: **supports**.

**Ch13.4 — caffeine blocks adenosine | Tier T2**
NINDS, *Brain Basics: Understanding Sleep*. (URL above)
> "Release of a chemical called adenosine from cells helps make you feel sleepy. Caffeine counteracts sleepiness by blocking the actions of adenosine."
Number check: NA. Evidence: **supports**.

**Ch05.16 — deep sleep front-loaded early | Tier T2**
NINDS, *Brain Basics*. (URL above)
> "Stage 3 non-REM sleep is the period of deep sleep that you need to feel refreshed in the morning. It occurs in longer periods during the first half of the night."
Number check: NA. Evidence: **supports**.

**Ch10.15 — REM = memory + emotional processing | Tier T2 (with nuance)**
NINDS, *Brain Basics*. (URL above)
> "Memory consolidation most likely requires both non-REM and REM sleep." / "The amygdala, an almond-shaped structure involved in processing emotions, becomes increasingly active during REM sleep." / "dreaming may help you process your emotions."
Number check: NA. Evidence: **partial** — emotional processing strongly supported; memory consolidation per NINDS needs *both* non-REM and REM, so attributing memory solely to REM is a simplification. **Author flag: consider "REM is central to memory and emotional processing" rather than "where it happens."**

**Ch06.12 — evening/screen light suppresses melatonin | Tier T2**
SHF, *Melatonin* (2024). https://www.sleephealthfoundation.org.au/sleep-disorders/melatonin
> "Normally its production is reduced by being in bright light."
Number check: NA (the screen/short-wavelength + 17-lux specifics route to T3). Evidence: **supports** (concept).

**Ch06.16 — melatonin useful for jet lag / shift | Tier T2**
SHF, *Melatonin*. (URL above)
> "...to help reset your internal body clock to a different time in conditions where it is out of synchrony with time of day, such as with jet lag or advanced or delayed sleep phase syndrome."
Corroborating: AASM circadian practice guideline indicates timed melatonin for jet lag disorder (to be quoted directly in Step 3). Evidence: **supports**.

**Ch06.17 — melatonin 0.5–1 mg, 30–60 min before | Tier T2**
SHF, *Melatonin*. (URL above)
> "Daily doses of 0.5 mg to 5 mg appear similarly effective, although sleep onset may be quicker at the higher dose. There does not appear to be any advantage in taking more than this." / "the best time (for the slow-release type particularly) is about an hour before you go to bed."
Number check: book 0.5–1 mg / 30–60 min — **consistent** (within SHF's 0.5–5 mg "no advantage to more"; ~1 h ≈ 30–60 min). Evidence: **supports**.

**Ch16.5 — morning light strongest circadian cue | Tier T2 (partial)**
NINDS, *Brain Basics*. (URL above)
> "Factors that influence your sleep-wake needs include medical conditions, medications, stress, sleep environment, age, and what you eat and drink. Perhaps the greatest influence is the exposure to light."
Number check: NA. Evidence: **partial** — confirms light is the dominant cue; "morning" specificity (phase-response) routes to T3.

**Ch15.16 — CBT-i: don't lie awake, get up (stimulus control) | Tier T1**
AASM, *New guideline supports behavioral, psychological treatments for insomnia* (2020). https://aasm.org/new-guideline-supports-behavioral-psychological-treatments-for-insomnia/
> "The guideline includes one strong recommendation — which is one that clinicians should follow under most circumstances — for the use of cognitive behavioral therapy for insomnia. CBT-I combines one or more cognitive therapy strategies with education about sleep regulation plus behavioral strategies such as stimulus control instructions and sleep restriction therapy."
Corroborating (the get-up instruction): NINDS, *Brain Basics*: "Don't lie in bed awake. If you can't get to sleep, do something else, like reading or listening to calming music, until you feel tired."
Number check: NA. Evidence: **supports**.

**Ch05.12 + Ch14.8 — alcohol sedates, fragments sleep / disrupts architecture | Tier T2**
SHF, *Caffeine, Food, Alcohol, Smoking and Sleep* (2025). https://www.sleephealthfoundation.org.au/sleep-topics/caffeine-food-alcohol-smoking-and-sleep
> "Although alcohol will make you feel sleepy, and may help you fall asleep at night, alcohol will also disrupt your sleep by interfering with sleep architecture (how your body cycles through the normal stages of sleep), resulting in a highly fragmented and disrupted sleep episode causing poor sleep quality, and next day tiredness."
Number check: NA. Evidence: **supports** (concept). Explicit "REM suppression / slow-wave fragmentation" mechanism → T3 refinement.

**Ch14.13 — REM rebound: vivid/disturbing dreams | Tier T2**
SHF, *Caffeine, Food, Alcohol, Smoking and Sleep*. (URL above)
> "...in the second half of the night, sleep after drinking alcohol is associated with more frequent awakenings, night sweats, nightmares and more frequent awakenings to use the bathroom..."
Number check: NA. Evidence: **supports** (nightmares confirmed; "REM rebound" label → T3).

**Ch23.7 — eat ~3 h before bed | Tier T2**
SHF, *Caffeine, Food, Alcohol, Smoking and Sleep*. (URL above)
> "It is best if you allow 2-3 hours between having your last main meal of the day and going to bed."
Number check: book 3 h — **consistent** (top of SHF's 2–3 h). Evidence: **supports**. "Research consistent that closer = worse" meta-analytic support → T3.

## B. Concept-confirmed at T1/T2, specific number/mechanism still pending (3 facts)

**Ch06.19 — high-dose melatonin: no added benefit (grogginess/blunting pending).**
SHF: "There does not appear to be any advantage in taking more than this." Confirms "more isn't more"; the *morning grogginess / blunted sensitivity* specifics need T3.

**Ch12.11 — core temp drops before sleep (the 1–2° figure pending).**
SHF *Melatonin*: "your core body temperature will go down slightly at this time." NINDS (Stage 2): "Your body temperature drops." Concept confirmed; the **1–2°** magnitude → T3 (watch unit: many sources quote ~1–2 °F ≈ 0.5–1 °C).

**Ch14.12 — second-half-of-night awakenings (the 3–4am / metabolic-rebound mechanism pending).**
SHF: "in the second half of the night... more frequent awakenings." Timing confirmed; HR/BP "metabolic rebound" mechanism → T3.

## C. Not found at T1/T2 — route to Step 3 (43 facts)

These are mostly (a) specific numbers no authoritative body publishes, (b) physiology/mechanisms only primary literature states, or (c) the supplement doses. Listed by cluster:

- **Caffeine:** Ch13.6 (6-h half-life — SHF/FDA give "3–7 h effects / up to 24 h elimination," neither states a 6-h half-life; **number unverified**), Ch07.18 (late caffeine → cortisol).
- **Adenosine:** Ch05.5 (deep sleep *clears* adenosine overnight — NINDS supports build-up, not the clearance specific).
- **Melatonin:** Ch06.9 (peak ~midnight–1am), Ch06.18 (OTC ≫ natural production).
- **Light/screens:** Ch15.21 (17-lux threshold), Ch15.22 (TV 5 lux vs phone 25–50 lux), Ch21.3 (content > light), Ch16.8 (outdoor vs indoor lux).
- **Cortisol:** Ch07.7 (CAR precedes waking), Ch07.8 (peak first hour), Ch07.17 (~2am melatonin ease / cortisol fills gap), Ch07.20 (sleep loss raises cortisol).
- **Alcohol:** Ch14.2 (zero-alcohol "recommended position" — bodies say *limit/time it*, not zero → possible T5/flag), Ch14.9+10 (−15 min / −40 min figures).
- **Temperature:** Ch12.10 (16–26 °C), Ch12.13 (warmth fragments, esp. REM), Ch12.14 (REM suspends thermoregulation), Ch20.6 (exercise temp 30 min–2 h).
- **Trackers:** Ch10.11 (>85% efficiency — figure corroborated in search, needs a real source quote), Ch10.19 (staging error 20–30 min).
- **Supplements:** Ch11.6, Ch11.7, Ch11.8, Ch11.9, Ch11.10, Ch11.11 (all RCT/meta-analysis territory).
- **Self-control:** Ch13.10+Ch24.5.
- **Appetite:** Ch24.6 (ghrelin↑/leptin↓), Ch24.7 (ghrelin→sweet/fatty), Ch24.11 (reactive sugar crash).
- **Vagus/breathing:** Ch18.18, Ch18.21, Ch18.29.
- **CBT/ACT:** Ch15.17 (ACT-i acceptance).
- **Exercise:** Ch20.17 (morning exercise→cortisol), Ch20.18 (≥4 h before bed — likely mixed; NINDS says "not within a few hours").
- **Regularity:** Ch17.13 (bedtime deviation → HR/recovery).
- **Food:** Ch23.13a (protein→glucose), Ch23.13b (carbs→tryptophan→melatonin).
- **Menopause/HRT:** Ch04.20, Ch04.21 (Menopause Society / IMS sources located; verbatim to be pulled in Step 3 — likely T1/T2 once fetched).
- **Dehydration:** Ch22.4 (dehydration→cortisol — limited direct evidence; watch).

## Step 2 tally

| Bucket | Count |
|--------|-------|
| Resolved at T1/T2 | 13 |
| Concept-confirmed, number/mechanism pending | 3 |
| Not at T1/T2 → Step 3 | 43 |
| **Total** | **59** |

**Status:** Step 2 complete.

---

# STEP 3 RESULTS — Pass 1 (6 clusters: caffeine, cortisol, melatonin, alcohol, menopause, temperature)

All quotes below retrieved and read this session (Europe PMC abstracts via REST, + earlier
fetches). web_fetch rate limits interrupted this pass — items marked **PENDING** still need
a verbatim source and will be finished on resume.

## Solidly sourced this pass

**Ch07.18 — late caffeine is a cortisol stimulus | T3 | supports**
Lovallo WR et al. (2005), *Psychosom Med* 67:734–739. DOI 10.1097/01.psy.0000181270.20036.06
> "Caffeine increases cortisol secretion in people at rest or undergoing mental stress... caffeine challenge doses caused a robust increase in cortisol across the test day (p < .0001)... cortisol levels were again elevated between 1:00 PM and 7:00 PM (p = .02 to .002) after the second caffeine dose taken at 1:00 PM."
Number check: NA. Note: tolerance reduces but does not eliminate the response in daily users.

**Ch07.20 — sleep deprivation raises cortisol | T3 | supports**
Leproult R et al. (1997), *Sleep* 20:865–870. DOI 10.1093/sleep/20.10.865
> "After partial and total sleep deprivation, plasma cortisol levels over the 1800-2300-hour period were higher on day 2 than on day 1 (37 and 45% increases, p = 0.03 and 0.003, respectively)... even partial acute sleep loss delays the recovery of the HPA from early morning circadian stimulation."
Number check: book gives no figure; +37–45% next-evening elevation supports.

**Ch07.7 — CAR precedes waking | T3 | PARTIAL — framing flag**
Fries E, Dettenborn L, Kirschbaum C (2009), *Int J Psychophysiol* 72:67–73. DOI 10.1016/j.ijpsycho.2008.03.014
> "the secretion of cortisol from the adrenal glands follows a diurnal cycle with a profound increase after awakening. This increase after awakening, a phenomenon termed the cortisol awakening response (CAR), appears to be a distinct feature of the... (HPA) axis, superimposing the circadian rhythmicity of cortisol secretion."
Number check: NA. **AUTHOR FLAG:** the CAR is defined as the surge *after* awakening (peaking ~30–45 min later), superimposed on the circadian rise. The book's "before you open your eyes... called the cortisol awakening response" mislabels the pre-waking circadian rise as the CAR. Suggest: cortisol rises through the late night (circadian), then surges further in the 30–45 min after waking (the CAR).

**Ch07.8 — cortisol peaks early then declines | T3 | supports (via Fries, above)**
Diurnal cycle with post-waking peak then daytime decline is the standard description; Fries confirms the "profound increase after awakening" superimposed on the circadian rhythm.

**Ch14.8 — alcohol suppresses REM | T3 | supports**
Ebrahim IO et al. (2013), *Alcohol Clin Exp Res* 37:539–549. DOI 10.1111/acer.12006
> "at high doses, REM sleep reduction in the first part of sleep is significant. Total night REM sleep percentage is decreased in the majority of studies at moderate and high doses... The onset of the first REM sleep period is significantly delayed at all doses."
Number check: NA. Evidence: **supports** (REM portion).

**Ch05.12 + Ch14.8 — alcohol "suppresses / fragments deep (slow-wave) sleep" | T3 | CONTRADICTS ⚠**
Ebrahim IO et al. (2013), same review.
> "The majority of studies, across dose, age and gender, confirm an increase in slow wave sleep (SWS) in the first half of the night relative to baseline values... Total night SWS is increased at high alcohol doses across gender and age groups."
Number check: NA. Evidence: **contradicts.** **AUTHOR FLAG (important):** the strongest review finds alcohol *increases* SWS in the first half of the night — the opposite of "suppresses slow-wave sleep" / "fragments deep sleep." Alcohol's real signature is *REM* suppression + *second-half* fragmentation, not deep-sleep suppression. This also undercuts the Ch05 mechanism ("alcohol suppresses SWS so adenosine doesn't clear"). Recommend rewording to: alcohol front-loads/*increases* early-night SWS but suppresses REM and fragments the *second half* of the night.

**Ch14.12 — second-half rebound / wakeful 3–4am | T2+T3 | supports**
Ebrahim 2013: "an increase in sleep disruption in the second half of sleep." + SHF (Step 2): "in the second half of the night... more frequent awakenings." Concept supported; literal "3–4am" and HR/BP "metabolic rebound" mechanism still finer-grained than sources state.

**Ch12.13 — warmth fragments sleep (REM & SWS) | T3 | supports**
Okamoto-Mizuno K, Mizuno K (2012), *J Physiol Anthropol* 31:14. DOI 10.1186/1880-6805-31-14
> "The stereotypical effects of heat or cold exposure are increased wakefulness and decreased rapid eye movement sleep and slow wave sleep. These effects of the thermal environment on sleep stages are strongly linked to thermoregulation."
Number check: NA. Evidence: **supports.** (Book's "especially REM" emphasis — review pairs REM with SWS; full text needed if REM-specific emphasis is to be cited.)

**Ch12.14 — REM suspends thermoregulation | T3 | PARTIAL**
Okamoto-Mizuno links thermal effects to thermoregulation but the abstract doesn't state the specific "thermoregulation is largely suspended during REM" (poikilothermia). Well-established physiology; needs the full-text line or a physiology source. PENDING verbatim.

## PENDING this pass (rate-limited / need verbatim)

- **Ch13.6** caffeine 6-h half-life — incidental modeling value 4.0 h (Agboola 2026); literature range 3–7 h, mean ~5 h. **Book's 6 h sits at the upper end** — get EFSA/PK-review verbatim; likely a "number-high" flag.
- **Ch07.17** cortisol nadir ~midnight, rises in latter half of night (~4 h before wake) — search indicates nadir ~midnight, rise ~02:00–03:00; need verbatim.
- **Ch06.9** melatonin peak — literature says peak ~03:00–04:00 ("middle of the night"); **book's "midnight or one" is earlier than the cited peak** → likely number flag. Need verbatim.
- **Ch06.18 / Ch06.19** OTC ≫ natural; high-dose grogginess/blunting — search: brain makes ~0.3 mg/24 h vs OTC 1–10 mg ("supraphysiologic"); need verbatim source.
- **Ch14.2** "zero alcohol is the recommended position" — bodies advise *limit/timing*; WHO says no safe level for *health* generally (not sleep-specific) → likely **T5/soften flag**.
- **Ch14.9 + Ch14.10** −15 min / −40 min restorative loss — Ebrahim review is explicitly *qualitative* and gives **no minute figures**; these specific numbers so far have **no source** → likely NONE/weak; flag.
- **Ch04.20 / Ch04.21** menopause estrogen/progesterone drop; HRT restores sleep — Menopause Society / IMS located; verbatim fetch was rate-limited. Likely T1/T2 on resume.
- **Ch12.10** 16–26 °C — author-flagged "popular sources"; likely T6.
- **Ch12.11** core temp −1–2° — SHF/NINDS confirm a drop; magnitude + °C/°F unit check PENDING.
- **Ch20.6** exercise raises temp, 30 min–2 h to baseline — PENDING.

## Pass-1 flags for the author (headline items)

1. **Alcohol & deep sleep (Ch05.12/Ch14.8) — CONTRADICTED.** Best review says alcohol *increases* early-night SWS, not suppresses it. Reword toward "REM suppression + second-half fragmentation."
2. **CAR (Ch07.7) — mislabelled.** The cortisol awakening response is the *post-waking* surge, not the pre-waking rise.
3. **Caffeine 6-h half-life (Ch13.6)** and **melatonin peak "midnight–1am" (Ch06.9)** both look like **numbers on the wrong side of the cited ranges** (half-life usually ~5 h; melatonin peak ~3–4am) — confirm on resume.
4. **Alcohol −15/−40 min (Ch14.9/10)** — no source located yet; may be unciteable as stated.

## Pass 1 — additional sources (resumed)

**Ch04.21 — HRT may restore sleep | T3 | supports (with VMS caveat)**
Cintron D et al. (2017), *Endocrine* 55:702–711 (systematic review & meta-analysis). DOI 10.1007/s12020-016-1072-9
> "Menopausal hormone therapy improved sleep quality in women who had vasomotor symptoms at baseline [standardized mean difference −0.54 (−0.91 to −0.18), moderate quality evidence]. No difference was noted when women without such symptoms were analyzed separately or combined."
Corroborating (HT efficacy): NAMS 2022 Position Statement, *Menopause* 29:767–794, DOI 10.1097/GME.0000000000002028: "Hormone therapy remains the most effective treatment for vasomotor symptoms... and the genitourinary syndrome of menopause."
Number check: NA. Evidence: **supports**, and the meta-analysis's "only helps when VMS present" finding *matches* the book's framing ("if menopause is the only thing that changed, HRT may be enough"). Good alignment.

**Ch04.20 — menopause estrogen/progesterone drop worsens sleep | T3 | supports**
Cintron 2017 (above): "Sleep complaints are reported by 40-60 % of menopausal women." Mechanistic attribution to the estrogen/progesterone decline is covered in perimenopause narrative reviews (e.g., the ovarian-hormone pathophysiology literature); the prevalence + HT-reversal evidence supports the book's claim. Evidence: **supports**.

**Ch12.11 — core temperature drops before sleep | T3 qualitative + number flag**
Harding EC, Franks NP, Wisden W (2019), *Front Neurosci* 13:336. DOI 10.3389/fnins.2019.00336
> "sleep onset and a reduction in core temperature occur together. Non-rapid eye movement (NREM) sleep episodes are also accompanied by core and brain cooling... NREM onset is most likely when core temperature is at its steepest rate of decline."
Number check: the cooling is confirmed, but this abstract gives no magnitude. The commonly cited figure is ~0.5–1 °C (≈1–2 °F). **AUTHOR FLAG:** the book's "one to two degrees," read as Celsius (the book uses °C elsewhere), is roughly double the usual ~0.5–1 °C. If the intended figure was 1–2 °F, say so; otherwise consider "about half a degree to a degree (Celsius)."

## Pass 1 — items left at flag / low-tier / no-source (honest status)

- **Ch13.6 caffeine half-life:** no source states a "6-hour half-life." SHF (T2): effects "last 3 to 7 hours... up to 24 hours to fully eliminate." Pharmacology consensus ~5 h average (a 2026 modeling study gave 4.0 h). **FLAG: 6 h is the upper end; ~5 h is more typical.** Consider "about five hours" or "four to six hours."
- **Ch06.9 melatonin peak "midnight or one":** multiple secondary sources place the peak ~3–4 am ("middle of the night"); SHF (T2) only states melatonin "starts to go up about 2 hours before sleep." No single authoritative verbatim pinned for the exact peak this session. **FLAG: book's midnight–1am looks ~2–3 h early; verify and likely move later.** (Note: for a 10pm sleeper, a ~3–4am peak = mid-late sleep, consistent with the Ch07.17 "~2am" handover framing.)
- **Ch07.17 cortisol ~2am handover:** consistent with the consensus diurnal pattern (nadir ~midnight, rise begins ~02:00–03:00). Per your steer, "~2am" = ~4 h after a 10pm onset / latter half of night — that maps correctly. Verbatim still to be pinned (a circadian-cortisol review); evidence direction: **supports**.
- **Ch06.18 / Ch06.19 OTC≫natural & high-dose grogginess:** SHF (T2) supports "no advantage taking more than" low doses; the quantitative "body makes ~0.3 mg/night vs OTC 1–10 mg (supraphysiologic)" is widely stated but not yet pinned to one authoritative verbatim. Partial.
- **Ch12.10 16–26 °C:** inherently a "popular sources" claim (the book says so) → **T6**; fine as a soft statement, not a hard citation.
- **Ch12.14 REM suspends thermoregulation:** Okamoto-Mizuno ties thermal effects to thermoregulation but the specific poikilothermia-in-REM line needs the full text or a physiology source. Partial.
- **Ch20.6 exercise raises temp 30 min–2 h:** not yet sourced — PENDING.
- **Ch14.2 "zero alcohol is the recommended position":** authoritative bodies advise *limiting/timing*, not zero-for-sleep → likely **T5/soften**. PENDING verbatim.
- **Ch14.9 + Ch14.10 (−15 min / −40 min):** Ebrahim review is explicitly qualitative — **NO SOURCE** for these specific minute figures. Likely uncitable as written. **FLAG.**

## Pass 1 tally (19 facts in the 6 clusters)

| Outcome | Facts |
|---------|-------|
| Sourced — supports | Ch07.18, Ch07.20, Ch07.8, Ch14.8 (REM), Ch14.12, Ch12.13, Ch04.20, Ch04.21, Ch12.11 (qual.) |
| Sourced — **contradicts** | Ch05.12/Ch14.8 (alcohol↑SWS) |
| Sourced — **mislabel flag** | Ch07.7 (CAR) |
| **Number flag** (off-range/unit) | Ch13.6 (½-life), Ch06.9 (peak), Ch12.11 (°C/°F) |
| Low-tier T6 | Ch12.10 |
| No source found | Ch14.9, Ch14.10 |
| Partial / pending verbatim | Ch07.17, Ch06.18, Ch06.19, Ch12.14, Ch20.6, Ch14.2 |

**Status:** Step 3 Pass 1 complete.

---

# STEP 3 RESULTS — Pass 2 (clusters: supplements, appetite, vagus, light/screens, trackers, exercise)

web_fetch rate limits throttled this pass heavily; sourced items below have retrieved
verbatim quotes, the rest are identified-but-pending or routed onward.

## Solidly sourced this pass

**Ch24.6 — poor sleep raises ghrelin, lowers leptin | T3 | supports**
Spiegel K et al. (2004), *Ann Intern Med* 141:846–850. DOI 10.7326/0003-4819-141-11-200412070-00008
> "Sleep restriction was associated with average reductions in the anorexigenic hormone leptin (decrease, 18%; P = 0.04), elevations in the orexigenic factor ghrelin (increase, 28%; P < 0.04), and increased hunger (increase, 24%...) and appetite (increase, 23%...)."
Number check: book gives no figures; ghrelin↑/leptin↓ direction confirmed. Evidence: **supports**.

**Ch24.7 — ghrelin tilts cravings toward sweet/fatty | T3 | supports (minor wording note)**
Spiegel 2004 (same):
> "...especially for calorie-dense foods with high carbohydrate content (increase, 33% to 45%; P = 0.02)."
Number check: NA. Evidence: **supports.** Note: the study shows the shift toward calorie-dense, *high-carbohydrate* (sweet/starchy) foods; "fatty" is a reasonable extension but the data centre on carbs. The specific "ghrelin acts on the reward system" mechanism is a further step (supported elsewhere) — wording is fine.

**Ch11.8 — ashwagandha (KSM-66) reduces stress response / aids sleep | T3 | supports**
Cheah KL et al. (2021), *PLoS One* 16:e0257843 (systematic review & meta-analysis). DOI 10.1371/journal.pone.0257843
> "Ashwagandha extract exhibited a small but significant effect on overall sleep (Standardized Mean Difference −0.59; 95% CI −0.75 to −0.42)... Ashwagandha extract was also found to improve mental alertness on rising and anxiety level."
Evidence: **supports** (sleep + anxiety/stress). Cortisol-reduction specifically is shown in a separate stress meta-analysis (can add if wanted).

**Ch11.9 — ashwagandha 300–600 mg | T3 | supports (number consistent)**
Cheah 2021: "The effects on sleep were more prominent in the subgroup of adults diagnosed with insomnia, treatment dosage ≥600 mg/day, and treatment duration ≥8 weeks."
Number check: book 300–600 mg — **consistent** (≥600 mg is the clearly effective end). Timing ("late afternoon/evening") not specified by the meta.

**Ch18.18 — slow exhale stimulates the vagus | T3 | supports (mechanism)**
Russo MA, Santarelli DM, O'Rourke D (2017), *Breathe* 13:298–309. DOI 10.1183/20734735.009817 (AU authors)
> "Investigations into the physiological effects of slow breathing have uncovered significant effects on the respiratory, cardiovascular, cardiorespiratory and autonomic nervous systems... Key findings include effects on... heart rate variability... respiratory sinus arrhythmia, and sympathovagal balance."
Evidence: **supports** the slow-breathing→vagal/autonomic mechanism (the exact "exhale activates vagus via diaphragm" wording is in full text).

**Ch18.29 — longer exhale + pause slows heart rate | T3 | supports**
Russo 2017 (same) — names "respiratory sinus arrhythmia" (the inhale-speeds/exhale-slows-HR phenomenon) and HRV effects as key findings. Evidence: **supports** (RSA is exactly the inhale↑/exhale↓ heart-rate mechanism).

**Ch10.19 — tracker sleep-staging is less precise | T3 | supports (qual.); specific minutes not pinned**
Chinoy ED et al. (2021), *Sleep* 44:zsaa291. DOI 10.1093/sleep/zsaa291
> "epoch-by-epoch sensitivity was high (all ≥0.93), specificity was low-to-medium (0.18–0.54), sleep stage comparisons were mixed... devices tended to perform worse on nights with poorer/disrupted sleep."
Number check: confirms staging is the weak metric and total-sleep detection is strong (sensitivity ≥0.93), but the book's specific "20–30 min nightly / ~10 min weekly" staging error is **not** stated here. Evidence: **supports** the qualitative claim; the minute figure remains unpinned (consistent with the broader validation literature).

## Identified but verbatim PENDING (rate-limited)

- **Ch20.18 — finish vigorous exercise ≥4 h before bed** → Stutz J et al. (2019), *Sports Med* 49:269–287 (meta-analysis, PMID 30374942). Search-level finding: evening exercise generally does *not* harm sleep; only **vigorous exercise ending ≤1 h before bed** impairs it. **This contradicts the book's "4 hours" rule (and the book already hedges that the studies were on healthy adults).** Likely **T3, evidence = contradicts/mixed → soften the 4-hour figure.** Verbatim to pull on resume.
- **Ch11.6 / Ch11.7 — phosphatidylserine blunts evening cortisol; 300–500 mg** → Monteleone P et al. (1992), *Eur J Clin Pharmacol* 42:385–388 (DOI 10.1007/BF00280123). Search-level: PS 800 mg/day blunted ACTH/cortisol response to stress. **Number caution:** the classic cortisol-blunting evidence used ~400–800 mg; the book's 300–500 mg is at/below the studied range, and the cortisol studies were exercise-stress, not "before bed." Verbatim pending.
- **Ch10.11 — sleep efficiency >85%** → Ohayon M et al. (2017), *Sleep Health* 3:6–19 (National Sleep Foundation quality recommendations) is the standard source; SE ≥85% is the conventional "good" threshold. Verbatim pending.

## Not yet researched (carry to Pass 3)

Light/screens: Ch15.21 (17 lux), Ch15.22 (TV 5 / phone 25–50 lux), Ch21.3 (content > light), Ch16.8 (outdoor≫indoor lux). Adenosine: Ch05.5 (deep sleep clears adenosine). Supplements: Ch11.10/Ch11.11 (Mg L-threonate — **expected weak/flag**, human sleep evidence thin). Self-control: Ch13.10/Ch24.5. Sugar crash: Ch24.11. Dehydration: Ch22.4. Food: Ch23.13a/b. Morning exercise→cortisol: Ch20.17. ACT-i: Ch15.17. Plus Pass-1 leftovers (Ch06.18/19, Ch12.14, Ch20.6, Ch14.2).

**Status:** Step 3 Pass 2 partially complete — 7 facts newly sourced with verbatim; 3 high-value pending (Stutz/PS/Ohayon, rate-limited); remainder carried to Pass 3. Headline new flag: **Ch20.18 (4 h before bed) likely contradicted — evidence supports ~1 h for most people.**



---

## Worked example — "summary plus sources" format (Ch03.1, CBN)

Reference example for the **summary plus sources** house style (defined in `CLAUDE.md`).
This is how a no-clean-cut-evidence item is resolved: accept the prose, attach a short honest
endnote, and keep the hard numbers here in the working file (never in the endnote itself).

**Claim:** Ch03.1 — CBN "supposedly even more targeted for sleep than CBD."
**Resolution:** accept + endnote. Endnote filed in `endnotes-draft.md`.

**Endnote (author voice, no statistics):**
> There's some evidence cannabinoids can aid sleep, but it's weak — a 2025 meta-analysis found the benefit came mainly from THC-type compounds, with no significant effect for CBD alone, and the only human CBN trial showed just a small reduction in night-time waking. Nothing shows CBN is "more targeted" than CBD. I'm describing what the forums promised, not what the science proves.

**Sources (in the endnote):**
- da Silva et al. 2025, *Sleep Medicine Reviews* — https://doi.org/10.1016/j.smrv.2025.102156
- Bonn-Miller et al. 2024, *Exp Clin Psychopharmacol* — https://doi.org/10.1037/pha0000682
- Saleska et al. 2024, *J Am Nutr Assoc* — https://doi.org/10.1080/27697061.2023.2203221

**Hard numbers (kept here, not in the endnote):**
- da Silva GHS et al. (2025), *Sleep Med Rev* 84:102156 (PMID 40929927). Systematic review + meta-analysis, 6 placebo-controlled RCTs, N=1,077. Cannabinoids vs placebo on subjective sleep quality: SMD 0.53 (95% CI 0.03–1.02; p=0.04; I²=88% — high heterogeneity). Subgroups: non-CBD cannabinoids SMD 0.82 (95% CI 0.24–1.40; p=0.005); CBD-only SMD 0.13 (95% CI −0.38–0.65; p=0.61, NS).
- Bonn-Miller MO et al. (2024), *Exp Clin Psychopharmacol* 32(3):277–284 (PMID 37796540; DOI 10.1037/pha0000682). Double-blind placebo-controlled RCT of CBN ± CBD; 20 mg CBN reduced night-time awakenings but did not improve sleep onset or overall sleep quality.
- Saleska JL et al. (2024), *J Am Nutr Assoc* 43(1):1–11 (PMID 37162192; DOI 10.1080/27697061.2023.2203221). N=1,793; no placebo arm (comparator = CBD isolate). Adding 15 mg CBN to 15 mg CBD gave no significant benefit; CBD did not exceed 5 mg melatonin. Industry-run (Radicle Science). Does not test CBN alone.
- Supporting context: Engeli BE et al. (2025), *Nutrients* 17(3):489 — DFG/SKLM expert review found no scientific evidence substantiating CBD sleep claims at supplement doses (plus a liver-enzyme safety signal at higher intakes).
