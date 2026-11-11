# Endnote review log (cumulative)

One running list of points found while collecting source text, for you to work through when deciding whether any endnote needs updating. New batches are appended at the bottom; existing items are never rewritten, only their Status changes when you decide.

How to read it: each item says where the endnote is, what the endnote says, what the source page or abstract says, and which source file holds the text. These are factual observations only. No summaries or fixes are proposed here. Changes to /book/endnotes.md go through a clean copy in /audit/ as usual.

Status key: OPEN (not yet reviewed) / KEEP (reviewed, no change) / CHANGE (needs an edit) / ?  (needs more checking)

Findings so far are based on the abstract unless the source file says FULL TEXT.

---

## Batch 1 (2026-10-15)

| # | Status | Chapter and note | Type | Source file |
|---|---|---|---|---|
| 1.1 | OPEN | Ch3 — Is CBN really more sleep-targeted than CBD? | Description of source differs from paper | bonnmiller-2024-cbn-cbd-sleep.md |
| 1.2 | OPEN | Ch3 — Is CBN really more sleep-targeted than CBD? | Description of source differs from paper | saleska-2024-cannabinoid-formulations-sleep.md |
| 1.3 | OPEN | Ch3 — Is CBN really more sleep-targeted than CBD? | Wording differs from abstract | dasilva-2025-cannabinoids-sleep-quality.md |
| 1.4 | OPEN | Ch1 — Is poor sleep linked to serious disease? | Cited page does not name some listed conditions | cdc-2024-cdi-sleep.md |
| 1.5 | OPEN | Ch1 — Is poor sleep linked to serious disease? | Figure in note vs abstract | sabia-2021-sleep-duration-dementia.md |
| 1.6 | OPEN | Ch3 — Can anyone truly function on little sleep? | Detail not checkable from abstract | he-2009-dec2-sleep-length.md |
| 1.7 | OPEN | Ch2, Ch7, Ch22 — Hill 2008 citations | Citation formatting inconsistent | hill-2008-exercise-cortisol-threshold.md |

### 1.1 Bonn-Miller 2024 (Ch3, CBN vs CBD)
- Endnote source line: "Bonn-Miller MO et al. 2024, *Exp Clin Psychopharmacol* — human CBD trial; no significant sleep effect."
- The DOI in the endnote (10.1037/pha0000682) leads to: "A double-blind, randomized, placebo-controlled study of the safety and effects of CBN with and without CBD on sleep quality" (Exp Clin Psychopharmacol 2024;32(3):277-284).
- Abstract: participants got placebo, 20 mg CBN, or 20 mg CBN with 10, 20 or 100 mg CBD for seven nights. Versus placebo, 20 mg CBN gave a nonsignificant effect on sleep quality (p = .082) and significantly fewer awakenings (p = .025) and less overall sleep disturbance (p = .023). No difference from placebo for sleep onset latency, WASO or daytime fatigue. "The addition of CBD did not positively augment CBN treatment effects."
- So the paper is a CBN trial, not a CBD-only trial. Ask: is this the paper you meant to cite for "no significant sleep effect for CBD alone"?

### 1.2 Saleska 2024 (Ch3, CBN vs CBD)
- Endnote source line: "Saleska JL et al. 2024, *J Am Nutr Assoc* — the only published human CBN trial; small reduction in night-time waking only."
- Paper at the DOI (10.1080/27697061.2023.2203221): "The Safety and Comparative Effectiveness of Non-Psychoactive Cannabinoid Formulations for the Improvement of Sleep" (J Am Nutr Assoc 2024;43(1):1-11), N = 1,793, six capsule products (15 mg CBD, 5 mg melatonin, and combinations including CBN and CBC), PROMIS sleep disturbance over 4 weeks.
- Abstract: all formulations improved sleep disturbance; "no significant differences in effect" between CBD isolate and CBD+CBN formulations (with or without CBC); no significant difference between CBD isolate and melatonin formulations. The abstract does not mention night-time waking.
- The Bonn-Miller paper above is also a human CBN trial, so "the only published human CBN trial" sits alongside it in the same note.
- Ask: which paper supports "small reduction in night-time waking only"? The Bonn-Miller abstract is where reduced awakenings with 20 mg CBN appears.

### 1.3 da Silva 2025 (Ch3, CBN vs CBD)
- Endnote: "meta-analysis; benefit came mainly from THC-type compounds."
- Abstract (Sleep Med Rev 2025;84:102156): six trials, 1,077 patients. Cannabinoids improved sleep quality (SMD 0.53; 95% CI 0.03-1.02). "Non-CBD cannabinoids demonstrated greater efficacy" (SMD 0.82); "CBD-only therapies showed no significant effect" (SMD 0.13; 95% CI -0.38-0.65). The abstract uses the term "non-CBD", not "THC-type". Full text (not available to me) may name the compounds.
- Minor: endnote author "da Silva SHN"; PubMed lists first author as Giovanna Hanike Santos da Silva.

### 1.4 CDC page (Ch1, serious disease)
- Endnote text: insufficient sleep "is associated with increased risk of heart disease, diabetes, high blood pressure, stroke, depression and obesity, and both the CDC and NINDS recognise these links."
- CDC page (Chronic Disease Indicators: Sleep, updated 3 June 2024) key points: "Insufficient sleep is linked to increased risk of anxiety, depression, obesity, heart disease, injury, and other serious conditions." The page text does not name diabetes, high blood pressure, stroke or dementia. It links to sub-pages that I did not fetch.
- NINDS Brain Basics page (cited in the same note) does name: high blood pressure, cardiovascular disease, diabetes, depression, obesity, and (in "Hope Through Research") strokes and cardiovascular disease.
- Ask: should CDC stay cited for the full list, or only for the conditions it names?

### 1.5 Sabia 2021 (Ch1, dementia)
- Endnote parenthetical: "about 8,000 UK adults followed for 25 years; six hours or less in one's 50s and 60s linked to about 30% higher dementia risk; observational."
- Abstract: 7,959 participants, 521 dementia cases, 25-year follow-up. Single-age hazard ratios for sleep of six hours or less versus seven hours: 1.22 (95% CI 1.01-1.48) at age 50, 1.37 (1.10-1.72) at age 60, 1.24 (0.98-1.57) at age 70 (imprecise). The "30% increased dementia risk" in the abstract refers to persistent short sleep at 50, 60 and 70 compared with persistent normal sleep.
- The note's wording ties the roughly 30% to "in one's 50s and 60s"; the abstract's 30% figure is for persistent short sleep across ages 50, 60 and 70.

### 1.6 He 2009 (Ch3, natural short sleepers)
- Endnote parenthetical: "DEC2 variant identified in one family."
- Abstract: a mutation (hDEC2-P385R) "associated with a human short sleep phenotype", plus transgenic mice with the mutation. The abstract does not say how many families. The free PMC version has no Methods in the main text (they are in the supplement, not fetched).
- Not verified either way from what I could read.

### 1.7 Hill 2008 (Ch2, Ch7, Ch22)
- Cited three ways: Ch2 as a PubMed link with pages "31:587"; Ch7 and Ch22 as the DOI with pages "31:587–591".
- The PubMed record gives 2008 Jul;31(7):587-91, DOI 10.1007/BF03345606, PMID 18787373, so these are the same paper.
- Content checks against the abstract: cortisol change +83.1% at 80% VO2max, +39.9% at 60%, +5.7% at 40% (not significant). Consistent with the Ch2 "approximately 83% at 80%" figure and the Ch7/Ch22 "rose at 60% and 80%, not at 40%" parenthetical.
- Only item here is consistency of the citation format.

### Checked, nothing to flag in batch 1
- Kim & Dimsdale 2007 (Ch2, Ch8): abstract says 63 articles; experimental stress decreased slow wave sleep, REM sleep and sleep efficiency and increased awakenings. Matches the Ch2 note.
- Kenny & McGinn 2017 (Ch2, Ch22): abstract describes prolonged postexercise elevation of body core temperature; cited as a review, which it is.
- NINDS Brain Basics (12 notes): not individually checked against each note yet; page text is saved in full for the later summary step.

---
(Batch 2 onward will be added below this line.)

## Batch 2 (2026-10-15)

### 2.1 Roenneberg 2012 (Ch5, "Does an irregular sleep schedule reduce deep sleep?") — OPEN
- Note text: "An irregular schedule shifts circadian timing, so a later sleep onset reduces the window available for slow-wave sleep. Social jetlag literature and standard sleep-stage data both support this mechanism." Source line: "Roenneberg T et al. 2012, *Curr Biol* 22:939–943 — social jetlag."
- The paper is "Social jetlag and obesity". Its abstract reports social jetlag associated with higher BMI, beyond sleep duration, and says social jetlag "results in chronic sleep loss".
- A search of the full text for "slow-wave", "slow wave", "deep sleep", "SWS" and "sleep stage" returned no matches. The paper does not address deep sleep or sleep stages.
- Ask: is this the right citation for the deep-sleep claim, or should it be tied only to the "irregular schedule shifts circadian timing" part? Does the note need a source that measures slow-wave sleep?

### 2.2 Sleep Foundation, *Sleep Latency* (Ch1, "Does dropping off instantly mean you're sleeping well?") — OPEN
- Note text: mean latency "below 5–8 minutes on the Multiple Sleep Latency Test is classified as pathological sleepiness; deliberate sleep deprivation drives it below one minute"; "very short latency can also occur in sleep apnoea and narcolepsy". The source line calls the page an "MSLT norms summary".
- Page as fetched: does not state a 5–8 minute range or a figure below one minute. It says latency under eight minutes "indicates increased sleepiness" and under eight minutes "could indicate a sleep disorder like narcolepsy". It does not link short latency to sleep apnoea.
- Page was updated July 2026, so its wording may have changed since the note was written. It is a commercial site (affiliate disclosure at the top).
- Ask: keep the page as a source for part of the claim, or add an MSLT source (e.g. a clinical guideline or review) for the 5–8 minute and sleep-deprivation figures and for apnoea?

### 2.3 Van Dongen 2003 (Ch3, "Can anyone truly function on little sleep?") — OPEN
- Endnote parenthetical: "48 healthy adults; 14 days at 4, 6 or 8 hours in bed".
- Abstract: n = 48 healthy adults across two experiments: the 14-day chronic restriction experiment (4, 6 or 8 h in bed) and a separate total sleep deprivation experiment. So 48 is the combined figure, not the number in the 14-day arms.
- Full text was not available (OUP bot check; abstract only). The split of participants between the two experiments could not be checked.
- Ask: change to "48 healthy adults across two experiments" or check the split against the full text.

### 2.4 CDC/NIOSH Module 3 (Ch3, "Is driving tired as risky as driving drunk?") — OPEN
- Note text: awake 17 hours is "comparable to" BAC 0.05%; 24 hours "roughly 0.10%". Source: CDC/NIOSH Module 3 (2020), page `mod3/08.html`.
- The page's title and text say impairments are "similar to" alcohol intoxication. The supporting references are on the Module 3 reference page (refs 14, 18, 19, 20, 21), which is a different URL from the one cited.
- Ask: change "comparable to" to "similar to", and consider citing the reference page or the underlying studies for the BAC equivalences.

### 2.5 Shi 2019 (Ch3, "Can anyone truly function on little sleep?") — KEEP?
- Endnote parenthetical: "ADRB1 variant identified in one family". Full text (PMC6763376) says kindred 50025 is a family segregating an autosomal dominant allele for familial natural short sleep. Consistent with "one family".

### 2.6 Berridge 2007 (Ch4, Ch8) — KEEP
- Ch4 cites ResearchGate; Ch8 cites the DOI. The PubMed record carries the same DOI, volume and pages, so these are one paper and the two links are alternatives for the same citation.
- Optional: use the DOI form in both places (the ResearchGate link was not loaded here and may be less stable).
- Only the abstract was available (PMC returned 404). Abstract says dopamine is "neither necessary nor sufficient" for hedonic "liking" and "appears necessary for normal 'wanting'". No claims in Ch4 or Ch8 were checked in detail against the full paper.

### 2.7 NAMS 2022 (Ch4, HRT and sleep) — OPEN
- The Ch4 note cites NAMS as a bare source line with no parenthetical, directly after Cintron on the next line (no blank line between them).
- The statement says hormone therapy improves sleep in women with bothersome night-time vasomotor symptoms by reducing night-time awakenings (Level II), and that estrogen "may have some effect on sleep, independent of VMS" (Level II, with "some evidence" for transdermal estrogen in perimenopausal women). The note says no clear improvement in women without hot flushes or night sweats.
- Ask: is the "independent of VMS" statement worth reflecting in the note, or is "no clear improvement" still the right summary?

### Checked, nothing to flag in batch 2
- Qaseem 2016 (Ch4): the guideline's recommendation wording was copied; consistent with the note that CBT-i is first-line for chronic insomnia and medication a short-term addition.
- Cintron 2017 (Ch4): systematic review; matches the endnote's description.
- Reichert 2022 (Ch3, Ch5): narrative review, abstract and full text saved; claims in the two notes were not individually checked against the full text.

## Batch 3 (2026-10-15)

### 3.1 Gardiner 2024 (Ch5; Ch15 ×4) — year — OPEN
- Endnote says 2024. PubMed gives the issue date as 2025 Apr (*Sleep Med Rev* 80:102030), published online 2024 Nov 19. The citation is also worded two ways in the endnotes ("*Sleep Medicine Reviews*" and "*Sleep Med Rev*").
- Ask: keep 2024 (online date) or change to 2025 (issue date), and make the journal name consistent.

### 3.2 Gardiner 2024 and Ebrahim 2013 — sleep-onset latency and deep sleep (Ch5, Ch15) — OPEN
- Ch15 "Does alcohol help you fall asleep…": "Alcohol does shorten the time it takes to fall asleep." Cited to both Ebrahim and Gardiner.
- Ebrahim abstract: "At all dosages, alcohol causes a reduction in sleep onset latency."
- Gardiner abstract: reductions in sleep onset latency and latency to deep sleep (N3) "were only observed following the consumption of a high dose of alcohol (≥0.85 g/kg or approximately five standard drinks)".
- The two abstracts disagree on dose. The Ch15 deep-sleep note ("at higher doses the primary change is a reduced latency to deep sleep") matches Gardiner.
- Ch15 / Ch5: deep sleep is "increased in the first half of the night at most doses". Ebrahim's abstract supports this ("the majority of studies… confirm an increase in slow wave sleep in the first half of the night"). Gardiner's abstract does not report slow-wave sleep amount.
- Ch15 REM claim (disruption even at about two drinks) matches Gardiner's abstract. Ebrahim's abstract says no clear trend on total-night REM at low doses.
- Ask: should the "fall asleep faster" note say it applies mainly at higher doses, and should the deep-sleep amount claim rest on Ebrahim alone?

### 3.3 Hajak, Riemann, Léger (Ch6, "Is overnight melatonin lower in people with insomnia?") — OPEN
- Note: "Several small studies have found…; not all agree."
- Léger 2004 had 517 insomnia patients aged ≥55 (plus 59 volunteers), so it is not small. It measured urinary 6-sulfatoxymelatonin, not blood melatonin.
- Hajak: 10 patients and 5 healthy controls (controls younger, 27 vs 41 years; age used as covariate). Matches "about 10 participants" and "more than five years" in the parenthetical.
- Riemann: 10 patients and 10 matched controls; abstract ends "still a matter of debate", matching the parenthetical.
- None of the three cited studies reports a null result, so "not all agree" has no source in this note.
- Ask: reword "small studies" (Léger is large), and add a source for "not all agree" or drop it.

### 3.4 Scott 2025 and Lack 2023 (Ch6 insomnia note) — OPEN
- Note: "Recent reviews support the broader idea that a weaker overnight rhythm is linked to trouble staying asleep."
- Scott 2025 is a study of 128 people with insomnia, not a review. It measured dim-light melatonin onset (timing). Its abstract finds DLMO linked to sleep timing, "but not with sleep continuity"; the phase angle between sleep onset and DLMO was linked to latency, duration and efficiency. It does not report overnight melatonin amount.
- Lack 2023 (review): "There is some evidence suggesting that sleep maintenance insomnia is associated with a blunted amplitude of circadian rhythm", and that this "requires considerably more circadian research".
- Ask: does the note need Scott 2025 as support for the "weaker rhythm" sentence, given it is a timing study with no association to sleep continuity? Is "reviews" (plural) right if only Lack is a review?

### 3.5 Lack 2023 (Ch9, "Can melatonin's overnight decline trigger an early wake?") — OPEN
- Abstract says early morning awakening insomnia "is associated with an advanced circadian phase (early timing)" and can be treated with evening bright light.
- The abstract does not mention melatonin falling or body temperature rising before waking. Full text not available, so this could not be checked beyond the abstract.

### 3.6 Cagnacci 1997 and Lok 2019 (Ch6, "Is melatonin a sleep signal rather than a sleeping pill?") — OPEN
- Note: melatonin "slightly lowers core body temperature and reduces alertness, moving the body toward a state in which sleep can happen."
- Cagnacci abstract: melatonin given during the day "decreases CBT by about 0.3 to 0.4 degree C". Supports "slightly lowers core body temperature".
- Lok abstract: 10 young adults; 5 mg melatonin in the daytime increased subjective sleepiness. It also says temperature changes "seem nonessential for melatonin-induced sleepiness". The note's wording links lower temperature and lower alertness as one pathway; Lok's abstract says the sleepiness did not depend on the temperature change.
- Both studies used daytime doses of melatonin, not the natural evening rise.

### 3.7 Sleep Health Foundation, *Melatonin* (six notes: Ch6 ×5, Ch7 ×1) — OPEN
The page (dated 26 Aug 2024) was copied in full. Against each note:
- "When does melatonin actually peak": the page gives no peak time or midnight–3 a.m. range; it says blood melatonin "starts to go up about 2 hours before you go to sleep" and "Levels increase at night".
- "Does evening light delay melatonin": the page says production "is reduced by being in bright light". It does not mention a delayed rise or blue light and screens.
- "When is taking melatonin genuinely useful": the page lists use as a sedative ("the most common use") and for resetting the body clock (jet lag, advanced and delayed sleep phase). It does not mention shift work or call the clock use "best-supported". It says "Daily doses of 0.5 mg to 5 mg appear similarly effective, although sleep onset may be quicker at the higher dose" and "about an hour before you go to bed". The note says no added benefit from higher doses; the page says nothing more than "no advantage in taking more than this" (above 5 mg).
- "Does a high dose carry over into the next morning": the page says only that melatonin "can cause sleepiness" and should not be taken before driving. It does not mention carry-over, grogginess or receptor desensitisation.
- "Do cortisol and melatonin work against each other" (Ch7): the page does not mention cortisol.
- "Is melatonin a sleep signal": the page supports the signal role, the rise before sleep and the slight fall in core temperature. It says "make you feel sleepy" for the sedative use.
- Ask: for each note, keep the page for the part it does support and add or move sources for the parts it does not.

### Checked, nothing to flag in batch 3
- Riemann 2002 parenthetical matches its abstract. Hajak 1995 figures match (see 3.3).

## Batch 4 (2026-10-15)

### 4.1 Wade 2010 (Ch6, "Does slow-release melatonin help you stay asleep?") — OPEN
- Endnote parenthetical: "791 adults, up to six months; total sleep time up 13 minutes in people with low natural melatonin, self-reported; manufacturer-affiliated."
- 791 adults and the six-month duration match the abstract. The 13-minute figure is in the full-text Results, long-term analysis only: low excretors, "a longer total sleep time was seen with PRM compared to placebo treated patients (estimated difference 13.1 min, 95% CI 1.0 to 25.2, P = 0.035".
- The abstract's primary (3-week) result is different: in low-melatonin patients PRM "did not differ from the placebo" on sleep latency; the sleep latency benefit was in elderly patients regardless of melatonin level (-19.1 versus -1.7 min; P = 0.002). The abstract's conclusion is that low melatonin production is "not useful in predicting responses".
- The Methods name Neurim Pharmaceuticals as the maker of the study drug (Circadin 2 mg). The competing-interests statement was not copied.
- The endnote link is the old PMC address, which now redirects. Optional: update to the current PMC address or the DOI (10.1186/1741-7015-8-51).
- Ask: should the note say the 13-minute gain was from the long-term analysis, and that the main short-term finding for low-melatonin people was no latency benefit?

### 4.2 Ferracioli-Oda 2013 (Ch6, same note) — OPEN
- Endnote parenthetical: "meta-analysis of 19 trials, mostly immediate-release; modest benefits."
- Abstract: 19 studies, 1683 subjects; latency 7.06 min shorter, total sleep time 8.25 min longer, sleep quality improved; effects "modest". Adults and children included.
- The word "immediate" does not appear anywhere on the PMC page text, so "mostly immediate-release" could not be confirmed (the Methods say only that drug formulation was extracted).
- The note's sentence "much of the research is linked to the manufacturer" is not covered by this source.

### 4.3 Lemoine 2007 (Ch6, same note) — KEEP?
- Parenthetical matches the abstract: 170 primary insomnia outpatients aged ≥55, 3 weeks, improved quality of sleep and morning alertness (Leeds Sleep Evaluation Questionnaire).
- The note says "the trials mainly measured how quickly people fell asleep"; Lemoine's outcomes were quality of sleep and morning alertness, not latency. Minor.

### 4.4 Menczel Schrire 2022 (Ch6, "Does a high melatonin dose carry over into the next morning?") — OPEN
- Note: "A high dose does not strengthen the sleep signal; it extends melatonin activity into the following morning, which can produce grogginess."
- Abstract: doses ≥10 mg in adults over 30; adverse events increased for "drowsiness, headache and dizziness" (rate ratio 1.40 [1.15, 1.69]) in a small low-bias subset; the review says high-dose safety evidence is limited. It does not mention morning carry-over, melatonin activity extending, or grogginess.
- Ask: is this the right source for the carry-over claim, or only for "drowsiness at high doses"?

### 4.5 Gerdin 2004 (Ch6, same note) — OPEN
- Endnote: "MT2 receptor desensitisation (rat/cell-line model)". The note says supraphysiological doses may blunt sensitivity through receptor desensitisation.
- Abstract: both physiological (300 pM) and supraphysiological (10 nM) melatonin reduced MT2 receptor number in cells; recovery after 300 pM was almost full by 8 h, but not after 10 nM even at 24 h. Exposure to physiological levels for 8 h ("mimicking the nocturnal surge") also desensitised functional responses (cells and rat SCN brain slice), and the authors conclude that nightly secretion desensitises the receptors.
- So the abstract shows desensitisation at normal nightly levels too, and the slower recovery after 10 nM. The note's framing (high doses blunt sensitivity) fits the recovery result but leaves out that normal nightly levels also do it.

### 4.6 Dickerson & Kemeny 2004 (Ch7 ×2, Ch8) — OPEN
- Abstract: 208 laboratory studies; cortisol responses occur for motivated performance tasks that are uncontrollable or socially evaluative; both together give the largest changes and longest recovery times; "contradict the belief that cortisol is responsive to all types of stressors".
- Ch7 "urgency": note says demands "that feel pressing, hard to control, or carry a risk of being judged" raise cortisol most. The abstract supports "uncontrollable" and "social-evaluative threat"; "pressing" or urgency is not in the abstract.
- Ch7 "return to baseline": abstract supports "largest and slowest to settle" for uncontrollable plus judged tasks. It does not say cortisol falls back to baseline.
- Ch8 "provocative content": note adds "rather than to whether the content is negative or positive"; the abstract is about laboratory tasks and does not address content or valence.

### 4.7 Wetherell 2015 (Ch7, "Does cortisol respond to urgency…") — OPEN
- Note: cortisol "rises more after waking on days when a challenge is expected." Parenthetical: "the anticipated challenge was an assessed, stressful task."
- Abstract: 23 healthy young adults; on the day they were to do a socially evaluative laboratory stressor, cortisol secretion was greater, "in particular" after awakening. Supports the note, but it is one small study of a single lab stressor, and the abstract calls it the first of its kind.

### 4.8 Fries 2009 (Ch7, "Does cortisol start rising before you open your eyes?") — OPEN
- The note says the CAR peaks 30–45 minutes after waking, on top of an overnight circadian rise.
- Abstract (review): "a profound increase after awakening", the CAR "superimposing the circadian rhythmicity of cortisol secretion". It does not give the 30–45 minute peak or describe a pre-waking rise. Full text not available.

### 4.9 Chan & Debono 2010 (Ch7 ×2, Ch22) — OPEN
- Full text read for the "Physiology of cortisol circadian rhythm" section: in 33 normal people, cortisol "reach lowest levels at around midnight, levels start to rise at around 02:00 to 03:00 and reach a peak at around 08:30". This supports the Ch7 "early hours" note (midnight low, rise 2–3 a.m.).
- Ch7 melatonin note says cortisol falls "to its lowest point around the start of the night"; the paper says midnight. Minor wording.
- The paper is about hydrocortisone replacement in adrenal insufficiency, not exercise or melatonin; it is used here only for the rhythm. The Ch22 parenthetical already says the timing benefit is inferred. The Ch7 notes carry no such parenthetical.

### 4.10 Riemann 2010 (Ch7, Ch17) — KEEP?
- Review: hyperarousal "from the molecular to the higher system level"; abstract lists neuroendocrine arousal among the evidence. The Ch17 parenthetical says "including raised stress-hormone activity"; the abstract says "neuroendocrine" and does not name stress hormones or cortisol. Full text not available.
- The Ch7 note uses it for the "hyperarousal model of insomnia"; the abstract supports that.

### Checked, nothing to flag in batch 4
- Lemoine's patient count, age and duration match the endnote (see 4.3 for the minor outcome point).

## Batch 5 (2026-10-15)

### 5.1 Lovallo 2005 (Ch7, "Does late caffeine raise cortisol?") — OPEN
- Endnote parenthetical: "48 men and 48 women; after five days without caffeine, a 1 p.m. dose raised cortisol through to 7 p.m.; in daily users the morning response disappeared but cortisol still rose after the afternoon dose."
- The abstract and Table 1 give 96 participants (48 + 48). The first sentence of the Methods says "Subjects were 98 healthy adults". That is an inconsistency inside the paper, not in the endnote.
- On test days the challenge was three capsules (250 mg at 9:00, 13:00 and 18:00). The last two saliva samples were at 18:00 (before the third capsule) and 19:00. So a rise at 19:00 may include the 18:00 dose, not just the 13:00 dose. The abstract says cortisol was elevated between 13:00 and 19:00 after the 13:00 dose in daily users, and "declined to control levels during the evening sampling period".
- The Results section was not read, only the abstract and Methods.
- Ask: should "through to 7 p.m." be checked against the Results figures, given the 6 p.m. dose?

### 5.2 Leproult 1997 (Ch7, "Does a bad night raise cortisol the next day?") — KEEP?
- Parenthetical matches the abstract: evening (18:00–23:00) plasma cortisol 37% higher after partial and 45% after total sleep deprivation, in normal young men; onset of the quiet period delayed by at least 1 hour.
- Note's "leaving the next night starting from a worse position" is an inference; the abstract says the findings suggest altered feedback and that sleep loss "could" affect stress resilience.
- The PubMed record shows no DOI; match is by author, journal, year and pages.

### 5.3 Fiorillo 2003 (Ch8, "Does the brain respond to novelty and unpredictability?") — OPEN
- Note: "Dopamine neurons fire most when it is unclear whether a reward will arrive." Parenthetical: "dopamine activity peaked when reward probability was 50%."
- Abstract: the phasic dopamine response "varied monotonically across the full range of probabilities" (it rose with reward probability). A separate, "previously unobserved" response, "a gradual increase in activity until the potential time of reward", covaried with uncertainty (which is highest at P = 0.5).
- So the 50% peak applies to the sustained ramp, not to the main firing response. The abstract does not name the species (the endnote says monkeys).
- Ask: reword to "a slower build-up of dopamine activity before the possible reward was greatest when the chance of reward was 50%".

### 5.4 Bunzeck & Düzel 2006 (Ch8, same note) — KEEP?
- Abstract: two fMRI studies; activity in the substantia nigra/ventral tegmental area (SN/VTA) was driven by novelty, not rarity, negative valence or targetness. Supports "new images activate the dopamine centres" with the caveat that fMRI measures SN/VTA activity, which the authors link to dopamine.

### 5.5 Clark & Zack 2023 (Ch8 ×3) — OPEN
- Abstract is a conceptual review: reward variability and frequency of exposure in gambling and digital products (infinite scroll, personalised recommendations) can give addictive potential through incentive salience and dopamine learning. It names gaming, shopping, social media and online pornography.
- Ch8 "Do screens desensitise the brain's reward system": note says heavy exposure "may reduce dopamine-receptor availability". The abstract does not mention receptor availability, desensitisation or tolerance.
- Ch8 "Are games and social feeds deliberately engineered": the title says "Engineered highs" and the abstract describes variability in these products; it does not say the designers' intent was deliberate.
- Full text not available.

### 5.6 Lack, Mercer & Wright 1996 (Ch9) — KEEP
- Parenthetical matches the abstract: temperature and melatonin rhythms advanced 2–4 hours in early-morning-awakening insomniacs; the 0–4 hour advances of sleepiness rhythms were not significant. The abstract gives no participant numbers (the endnote says "small").

### 5.7 Baron 2017 (Ch11, "Can sleep tracking increase anxiety about sleep?") — OPEN
- Note: tracker data drives "obsessive monitoring and heightened anxiety about sleep quality"; "the appropriate response for users who find tracking counterproductive is to set the tracker aside."
- Paper: three case reports. Discussion: trackers "reinforce sleep-related anxiety or perfectionism for some patients". The abstract describes "a perfectionistic quest for the ideal sleep". The cases "denied depression and anxiety" in two cases, and one patient had "elevated stress/anxiety symptoms".
- The paper does not recommend setting the tracker aside. Its recommendation is to incorporate trackers into cognitive behavioural therapy for insomnia. In one case the clinician suggested switching the device "from sensitive to normal mode", and another patient found tracker data helpful when tapering a sleeping pill. The authors state they cannot tell whether the tracker caused the sleep problem.
- Ask: is "set the tracker aside" the book's own advice (then no source needed) or attributed to Baron?

### 5.8 Shaffer & Ginsberg 2017 (Ch11, "Does HRV measure how well the nervous system balances its two modes?") — OPEN
- Note: "higher HRV is associated with greater parasympathetic (vagal) tone and better recovery capacity"; PNS and SNS contributions to HRV are "non-linear".
- Paper: "An optimal level of HRV is associated with health and self-regulatory capacity, and adaptability or resilience"; some "very high" values come from problems such as atrial fibrillation. It says the autonomic system is not a "zero-sum" teeter-totter. It has a heading "HF Power and RSA do not Represent Vagal Tone" and another "LnHF can Estimate Vagal Tone under Controlled Conditions". "Recovery" appears once, for heart-rate recovery after exercise.
- In this paper "non-linear" is a technical term for a class of HRV measures, not a description of PNS/SNS contributions. Suggested wording: "not a simple see-saw".

### 5.9 Chinoy 2021 (Ch11, "How accurate are consumer sleep trackers?") — KEEP?
- Parenthetical matches: 7 devices, 34 healthy young adults, three nights including a disrupted-sleep night. Abstract: devices "tended to perform worse on nights with poorer/disrupted sleep".
- Deep-sleep limits of agreement (Table 6, minutes, lower to upper): Fitbit Alta HR −73.8 to 61.7; Garmin Fenix 5S −53.0 to 65.1; Garmin Vivosmart 3 −57.5 to 64.9; ResMed S+ −54.8 to 83.8; SleepScore Max −36.3 to 77.7; EarlySense Live −66.8 to 138.6. Half-widths are about 57–69 min for five devices (EarlySense about 106). "Roughly ±55–75 min for the better devices" is close.
- Introduction raises concern that device algorithms working out time in bed without user input "may lead to errors". I found no section that tests correcting bedtime (the word "bedtime" appears only in Methods). Ch11 note says correcting the recorded bedtime improves accuracy; that is not confirmed here.
- Ask: is that bedtime-correction sentence supported by one of the other three trackers cited (Svensson, Robbins, Schyvens, not yet fetched)?

### 5.10 Ohayon 2017 (Ch11, "Is above 85% a good target for sleep efficiency?") — OPEN
- Note: an NSF panel "identified 85% or higher as a marker of good sleep quality across adult age groups."
- Only the abstract was available: the panel "agreed that these measures [including sleep efficiency] were appropriate indicators of good sleep quality across the life-span". No 85% figure and no age breakdown in the abstract; the 277-study review and modified Delphi method are named.
- Full text not available (publisher page not tried), so the 85% figure and "adult age groups" could not be checked. The statement that "the same figure is used… in behavioural treatment for insomnia" has no source in this note.
- Ask: check the full text for the 85% threshold by age group; add a source for the CBT-i use.

### Checked, nothing to flag in batch 5
- Bunzeck 2006 and Lack 1996 parentheticals match their abstracts (see 5.4 and 5.6).

## Batch 6 (2026-10-15)

### 6.1 Svensson 2024 (Ch11, "How accurate are consumer sleep trackers?" and "Does the Oura Ring have the most published validation research?") — OPEN
- Endnote parenthetical: Oura Gen 3, 96 adults; up to three nights averaged per person; deep-sleep limits still about ±65 min; mainly funded by Oura.
- Abstract confirms: 96 participants, 421,045 epochs, a maximum of three PSG nights per person with within-participant means. It also reports that Oura "did not significantly differ from PSG" for time in deep sleep and for wake after sleep onset.
- Not in the abstract: the ±65 min limits of agreement for deep sleep, and the funding statement. Only the abstract was available, so both are unchecked.
- Ask: check the full text (Bland-Altman limits for deep sleep; funding and conflict statements).

### 6.2 Robbins 2024 (Ch11, both notes) — OPEN
- Parenthetical matches: 35 adults, single inpatient night; the Apple Watch underestimated deep sleep by 43 min (p < 0.001). The funding statement reads "This research was funded by Oura Ring Inc."; one author is on the Oura Ring Medical Advisory Board.
- Oura note says a 2024 multi-device study "rated it most accurate in four-stage sleep staging (~79% agreement)". In the paper, four-stage epoch-by-epoch agreement was 76.3% for Oura (kappa 0.65), 70.9% for Fitbit (0.55) and 75.0% for Apple (0.60). The 79.5% figure is the top of Oura's sensitivity range (76.0–79.5%), and precision was 77.0–79.5%.
- The paper says Oura showed "substantial agreement" and the other devices "moderate agreement" on stages, but does not use the phrase "most accurate".
- Ask: replace "~79% agreement" with 76% agreement (or "76–80% sensitivity"), and soften "rated it most accurate" if wanted. Oura data came from the company, and the study is one night.

### 6.3 "Oura has the most published validation research" (Ch11) — OPEN
- Note: "the Oura Ring has accumulated the most published validation studies", with the caveat that "Oura may simply publish more than competitors".
- The two sources cited (Svensson, Robbins) are single validation studies. Neither counts or compares the number of validation studies across brands, so the "most published" claim has no source in the note.
- Kainec 2024 (batch 6) tested the Oura Gen 2, not the Gen 3.
- Ask: add a source that compares publication volume, or soften the claim.

### 6.4 Schyvens 2025 (Ch11, "How accurate…") — KEEP
- Parenthetical matches: WHOOP 4.0 overestimated deep sleep by 31.49 min (p < 0.001); single night; six devices. 62 adults, including people with suspected sleep apnoea, not only healthy sleepers.
- All six devices detected over 90% of sleep epochs but had low specificity for wake (29.39–52.15%). This is consistent with the note's statement that long still, awake periods are recorded as sleep.
- In this study all devices underestimated WASO (by 12.38–47.94 min). In Kainec the devices overestimated short wake and underestimated long wake (see 6.5).

### 6.5 Kainec 2024 (Ch11, "How accurate…") — KEEP
- Parenthetical matches: five devices; "The agreement between the devices and PSG-reported wake after sleep onset was poor for all devices."
- Nuance: the paper reports that all devices overestimated nights with shorter wake times and underestimated nights with longer wake times. The Oura tested was Gen 2. Young adults (18–30), one night, summary measures only (no epoch-by-epoch).

### 6.6 Lindberg 1990 and Pardo 2021 (Ch12, "Does the form of a supplement matter?") — KEEP
- Lindberg abstract: citrate more soluble than oxide in all acid conditions, and the rise in urinary magnesium after a 25 mmol load was higher for citrate; "magnesium citrate was more soluble and bioavailable than magnesium oxide". Matches the parenthetical. Absorption was measured by urinary rise in normal volunteers.
- Pardo abstract: systematic review, 14 studies selected from 433; "Inorganic formulations appear to be less bioavailable than organic ones, and the percentage of absorption is dose dependent". Matches the "systematic review supports this broad pattern" wording.
- Not checkable from abstracts: the note's caveat that "the studies are small and measure absorption in different ways", and that citrate specifically is among the organic forms compared. Full texts were not available.

### 6.7 Monteleone 1992 (Ch12, "Does phosphatidylserine reduce the evening cortisol response?") — OPEN
- Abstract: placebo-controlled study in 9 healthy men; phosphatidylserine (brain cortex derived) 800 mg/d for 10 days blunted the ACTH (P = 0.003) and cortisol (P = 0.03) responses to physical exercise, with no effect on GH and PRL. This matches "800 mg/day significantly blunted the ACTH and cortisol response to physical exercise" and the "exercise-induced, not evening" caveat.
- The note says "the original trial used 400–800 mg under exercise-stress conditions". The abstract gives only 800 mg/d. No 400 mg arm is mentioned (full text not available).
- No source in the note for: soy- or sunflower-derived PS as the current form, the brain-cortex source being unavailable, or the 400 mg before bed "consistent with clinical dosing".
- Ask: check the full text for a 400 mg arm; otherwise change to "800 mg/day". Add sources for the soy/sunflower and 400 mg statements, or mark them as the book's own advice.

### 6.8 Cheah 2021 (Ch12, "Does ashwagandha reduce stress and help sleep?") — KEEP?
- Parenthetical matches: meta-analysis; effects "more prominent" at dosage ≥600 mg/day and duration ≥8 weeks (SMD −0.59 overall; subgroups −0.69 for ≥600 mg and −0.68 for ≥8 weeks).
- The paper calls the overall effect "small but significant"; the note says "modest overall benefit". Close, but check wording.
- Four of the five trials used KSM-66 and one used Shoden, so "other standardised extracts have trials of their own" rests on a single trial here. The paper does not compare extracts, so "none has been shown to outperform the others" is not tested by it. The study is stated as unfunded.
- The abstract gives 400 participants in five trials, but the subgroup text reports 788, 995 and 1764 participants for sub-sets of the same trials. This is an inconsistency in the paper itself.

### 6.9 Chandrasekhar 2012 (Ch12, same ashwagandha note) — KEEP
- Parenthetical matches: KSM-66 (named in the text), 300 mg capsule twice daily, 64 enrolled (61 analysed for efficacy), 60 days. Serum cortisol was measured in the morning. Reduction from baseline: 27.9% (Ashwagandha) vs 7.9% (placebo), which rounds to 28% vs 8%.
- Within the paper, cortisol P values differ between the abstract (P = 0.0006) and the text (P = 0.006 for the day-60 difference, P = 0.002 for the change).
- "Source of Support: Nil", but the text says the extract was "provided by Ixoreal Biomed". The note's closing line ("the extract was often supplied by its manufacturer") fits this.

### 6.10 Langade 2019 (Ch12, same note) — KEEP
- Parenthetical matches: KSM-66, 300 mg capsule twice daily, 60 randomised (40 test, 20 placebo; 58 in per-protocol analysis), 10 weeks, actigraphy. Sleep onset latency was shorter on the extract at 10 weeks (p = 0.019), and sleep efficiency improved (75.63 to 83.48 vs 75.14 to 79.68).
- Acknowledgements: "The authors thank Ixoreal Biomed Inc… for supplying the KSM-66 Ashwagandha root extract used in the study." Authors declare no competing interests. Matches "extract supplied by manufacturer".
- Note: sleep onset latency also improved in the placebo group at 5 and 10 weeks.

### 6.11 Follow-up to 5.9 (Chinoy, bedtime correction) — OPEN
- Question left open in 5.9: is "devices make further errors when they guess bedtime for themselves, so correcting the recorded bedtime improves accuracy" supported by Svensson, Robbins or Schyvens?
- Robbins section 2.5 ("Wake Interpolation") says the device-estimated sleep interval could be shorter than the PSG time in bed and the missing epochs were treated as wake. It does not test correcting bedtime. Schyvens compared the devices over the 8-hour lights-out window. Svensson's full text was not available. No batch 6 source confirms the sentence.

### Checked, nothing to flag in batch 6
- None beyond the items above.

## Batch 7 (2026-10-17)

### 7.1 Mah & Pitre 2021 (Ch12, "Does magnesium L-threonate cross…" and "How much elemental magnesium…") — OPEN
- Matches: three RCTs, 151 older adults; sleep-onset latency 17.36 min shorter than placebo (95% CI −27.27 to −7.44); total sleep time +16.06 min, not significant. The "roughly 17 minutes" and "evidence quality is low" statements are supported.
- Quality wording: the note says the overall evidence is "low to moderate quality". The review says "All trials were at moderate-to-high risk of bias and outcomes were supported by low to very low quality of evidence".
- Dose: the note says "150–300 mg of elemental magnesium in the evening is within the range studied". The review reports daily elemental intake of 320 mg to 729 mg, "taken two to three times per day", using magnesium oxide and magnesium citrate. That is a daily total split across doses, not an evening dose. The abstract's conclusion refers to "less than 1 g quantities given up to three times a day".
- None of the three trials used L-threonate (oxide and citrate only). So the review does not speak to L-threonate.
- Ask: change "low to moderate" to "low to very low" if following Mah; restate the dose as a daily total (320–729 mg split two to three times daily) or mark the 150–300 mg evening range as the book's own inference.

### 7.2 Abbasi 2012 (Ch12, "Does magnesium L-threonate cross…") — KEEP
- Parenthetical matches: 46 older adults, 500 mg/day (elemental), 8 weeks. Sleep efficiency (P = 0.03), sleep onset latency (P = 0.02), serum cortisol lower (P = 0.008), melatonin higher (P = 0.007); total sleep time P = 0.37, not significant.
- Within the paper the abstract also lists a significant rise in "sleep time (P = 0.002)" alongside "total sleep time (P = 0.37)", which look like two different measures. The endnote follows the total sleep time result.
- Form and dose: tablets were magnesium oxide, 250 mg elemental magnesium twice a day. Oxide is the poorly absorbed form in Lindberg 1990 (batch 6), yet this trial found effects. This sits oddly with the Ch12 "form of a supplement" note, so you may want a sentence on it.
- Supports "may reflect correcting a shortfall": inclusion required dietary magnesium under 75% of the recommended intake and serum magnesium under 0.95 mmol/L. Age 60–75.
- The endnote links to a DOAJ record, which I did not load. Consider a DOI or PubMed link (PMID 23853635).

### 7.3 Liu 2016 (Ch12, "How much elemental magnesium…") — KEEP?
- This is a trial of MMFS-01 (a magnesium L-threonate compound, L-TAMS) in adults aged 50–70 with cognitive impairment, mainly about cognition. The abstract says "Due to the strong placebo effects on sleep and anxiety, the effects of MMFS-01 on sleep and anxiety could not be determined". This supports the note's "human sleep RCT evidence for L-threonate specifically is very limited".
- Dose: set to about 25 mg/kg/day: 1.5 g/day for 50–70 kg, 2 g/day for 70–100 kg, of MMFS-01. The Methods do not give an elemental magnesium amount, so the "≈144 mg elemental per 2 g" in the note is the book's own calculation (the note says so).
- Funding: funded by Neurocentria Inc., which "wrote the paper through an iterative review process".
- Ask: the note cites no source for the L-threonate dose line in the text shown; confirm that Liu is meant as the source for the 2 g figure.

### 7.4 Mason 2022 (Ch13, "Can light in the bedroom affect sleep without waking you?") — KEEP
- Matches: 20 healthy young adults (age 18–40); room light 100 lx on night 2 vs under 3 lx; heart rate higher and HRV lower during sleep; more N2 and less slow-wave and REM sleep (SWS P = 0.017, REM P = 0.033); melatonin similar; next-morning insulin resistance higher; no difference in wake episodes or fragmentation measures between conditions.
- Design nuance: parallel groups of 10 and 10. The room-light group slept night 1 in dim light and night 2 under room light; the control group slept both nights in dim light. The comparison is the change from night 1 to night 2 between groups, not the same people under both conditions.
- PubMed prints only the Significance statement as the abstract; the PMC page has both.

### 7.5 Harding, Franks & Wisden 2019 (Ch13, "Why is temperature…wired into the biology" and "How much does body temperature drop…") — OPEN
- Supported: core temperature decline and NREM onset occur together; heat is lost through vasodilation of the hands and feet (distal skin), seen up to 2 h before the first sleep episode; a "warm bath effect" section.
- Not found: the note says the core drop at sleep onset is "approximately 0.5–1 °C". I did not find a core-temperature drop figure in the paper. The 0.5 °C in the paper is the proximal-to-distal skin gradient, which falls from as much as 1.5 °C to about 0.5 °C. It also says warming the proximal skin by "less than 1°C" is enough to shorten sleep latency, and that the lowest core temperature comes about 2 h after lights-off.
- Mismatch in timing: the note says the steepest rate of change coincides "with the transition into slow-wave sleep". The paper says the steepest decline "intersects 'lights-off' and sleep onset" and NREM onset is most likely when core temperature is falling fastest. It does not mention slow-wave sleep in this context.
- "Core temperature begins falling in the hour before sleep onset" vs the paper's "up to 2 h prior".
- Ask: find a source for 0.5–1 °C (the Sleep Foundation page cites Kräuchi 2007 and says a fluctuation of about 2 °F, roughly 1 °C, through the night), and correct the slow-wave sleep timing and the one-hour wording.

### 7.6 Okamoto-Mizuno & Mizuno 2012 (Ch13, three notes) — KEEP?
- Supported (abstract): heat or cold exposure increases wakefulness and reduces REM and slow-wave sleep; in semi-nude subjects cold affects sleep stages more than heat; with bedding and clothing, heat exposure increases wakefulness and reduces SWS and REM, while cold exposure does not affect sleep stages. This supports "a warm room increases wakefulness and reduces REM and deep sleep".
- Bed climate: the text says bed climate temperature and humidity "are generally maintained around 32°C to 34°C, 40% to 60% relative humidity when normal sleep is obtained". The 29 °C note says the bed climate "stays roughly 32–34 °C across a wide range of room temperatures". The wording "across a wide range of room temperatures" is not in the passage I found. It reads as the temperature at which normal sleep occurs, not a measured constancy across room temperatures.
- Ask: check the paper for data on bed climate across room temperatures, or reword to "is generally around 32–34 °C when sleep is normal".

### 7.7 Cerri 2017 (Ch13, "Does the body stop regulating its temperature during REM sleep?") — KEEP?
- The abstract says "During REM sleep, the function of thermoregulation appears to be impaired", that cold exposure suppresses REM sleep, and that REM sleep may be seen as "a period of transient heterothermy". Supports the note.
- The parenthetical "evidence mainly from animal studies" could not be checked from the abstract, which does not say animal or human. Full text is available on PMC but was not searched for this.

### 7.8 Haskell 1981 (Ch13, "Where does the 29 °C…come from?") — KEEP
- Matches: six male subjects, nude except shorts, bed of nylon webbing, five ambient temperatures (21, 24, 29, 34 and 37 °C), 29 °C called thermoneutrality; 21 °C the most disruptive; cold generally more disruptive than warm.
- The abstract says nothing about bedding or covers beyond "nude except for shorts"; the note's "no bedding" reads as an inference from that. The note calls 29 °C "the least disruptive condition"; the abstract names 29 °C as thermoneutrality and 21 °C as the most disruptive.
- Abstract only (not in PMC; publisher page not tried).

### 7.9 Sleep Foundation, Best Temperature for Sleep (Ch13, "What bedroom temperature…") — OPEN
- The page says the best room temperature is "approximately 65 degrees Fahrenheit (18.3 degrees Celsius)" and that "most doctors recommend… between 65 to 68 degrees Fahrenheit (15.6 to 20 degrees Celsius)".
- The page's own Celsius range is wrong for its Fahrenheit range: 65–68 °F is 18.3–20 °C; 15.6 °C is 60 °F. The endnote body ("ranges quoted from the mid-teens to about 20 °C") follows the page's Celsius figure, while the parenthetical ("doctors' range 18–20 °C") follows the Fahrenheit figure. The note therefore contradicts itself.
- "They assume a typically covered sleeper" is not on the page; it is the book's own comment.
- Ask: pick one range. If following the page's Fahrenheit figures, use 18–20 °C and drop "mid-teens"; the 29 °C note elsewhere quotes "16–20 °C usually quoted for a covered sleeper", which should be made consistent too.

### 7.10 Basner 2011 (Ch13, "Do sudden noises disturb deep sleep without waking you?") — KEEP?
- Matches: 72 adults, 11 nights; "Excess arousal probability was on average 2.6 times higher than excess awakening probability"; excess awakening and arousal probability rose with maximum sound level, "more pronounced for noise levels ≥ 55 dB"; cardiac arousals "did not habituate across nights". Deep sleep (SWS) was significantly higher in noise-free control nights than pooled exposure nights, and arousals were more frequent in exposure nights. Awakening probability was lowest from SWS.
- Wording: the 2.6 ratio is of excess (above spontaneous) probabilities, not raw probabilities. The parenthetical "arousals about 2.6 times as likely as awakenings" drops "excess".
- The abstract describes noise effects on sleep structure as "subtle", with habituation. The note's "reduced deep sleep and increased brief arousals" is supported by the Results, but "subtle" is the authors' word.
- The note's second source (WHO) is not yet fetched (S071).

### Checked, nothing to flag in batch 7
- None beyond the items above.

## Batch 8 (2026-10-17)

### 8.1 WHO, Environmental Noise Guidelines (Ch13, "Do sudden noises disturb deep sleep without waking you?") — FIX
- The endnote's URL loads, but it is the short WHO/Europe fact sheet "Noise" (1 December 2011), not *Environmental Noise Guidelines for the European Region* (the 2018 guidelines). The page cites older WHO guidance: under 30 dB(A) in bedrooms for good sleep, and under 40 dB(A) Lnight outside bedrooms.
- The page says nothing on sudden noises, arousals or waking without remembering. If the note leans on WHO for a specific figure, that figure is not on this page.
- Ask: either change the title to match the page ("WHO/Europe, Noise fact sheet") or cite the 2018 guidelines document with its own URL. I have not located or saved the guidelines document.

### 8.2 SHF, Caffeine and Sleep (Ch14, "Does caffeine block the brain's sleep-pressure signal?") — KEEP?
- The page says caffeine "promotes alertness by inhibiting chemicals in the brain that promote sleep". It does not name adenosine or "sleep pressure". The Drake citation in the same note supports the six-hour finding.

### 8.3 Drake 2013 (Ch14, same note) — KEEP
- Full text checked: 400 mg caffeine at 0, 3 or 6 h before bed, 12 healthy sleepers. Objective total sleep time was reduced "between 1.1 to 1.2 hours" at each time point, so "more than an hour" is supported.
- "Participants did not notice": the discussion says there was a "lack of subjective awareness of caffeine-induced sleep disturbance" and "lack of perceived sleep disruption during early evening administration". The diary showed a 41 min reduction at 6 h that "approached significance (p = 0.08)". Supported, though it is a group finding, not every participant.
- The dose was 400 mg. If the note does not say so, a reader may assume a normal cup.

### 8.4 Juliano 2004 (Ch14, "Does caffeine wearing off feel like fatigue?") — KEEP
- The abstract lists fatigue and drowsiness among the validated withdrawal symptoms, and says abstinence from doses as low as 100 mg/day produced symptoms. Check the note's "even after stopping 100 mg a day" reads as "can occur after", not "does occur".

### 8.5 James and Rogers 2005 (Ch14, same note) — KEEP
- The abstract says withdrawal reversal accounts for almost all of caffeine's apparent benefit on performance and mood. Check the note does not say "all".

### 8.6 Agboola 2026 (Ch14, "What is caffeine's actual half-life?") — KEEP?
- It is not a new clinical study. It re-analyses concentration data from the PK-DB public database (37 caffeine patients at 100–400 mg; 38 paracetamol patients) and reports a half-life of 4.0 h. The note should not describe it as a trial or as the authors' own measurement.
- The Methods are saved; the one-compartment equation did not come through as text.

### 8.7 EFSA 2015 (Ch14, same note) — OPEN
- Only the abstract is free on the page I could load (the PDF was not opened). The abstract has no half-life and no "about 4 hours". The figure the note attributes to EFSA needs the full opinion to check.

### 8.8 SHF, Caffeine and Sleep, as a half-life source (Ch14, same note) — FIX
- The page gives no half-life. It says caffeine reaches peak levels within 30–70 minutes, "effects can then last 3 to 7 hours", and "it may take up to 24 hours to fully eliminate". The note's "broad range of ~3–7 h" is the effect duration, not a half-life.
- The page says metabolism is faster with nicotine and slower in pregnancy and with oral contraceptives. It does not mention SSRIs or "8–15 h" in pregnancy. Those two claims need another source.

### 8.9 SHF, Caffeine and Sleep (Ch14, "Does delaying the first coffee make caffeine work better?") — FIX
- This note cites SHF only, and the page says nothing about delaying the first coffee or cortisol. The claim has no support from the saved source.

### 8.10 Pilcher 2015 (Ch14, "Does sleep loss reduce self-control?") — KEEP?
- It is a non-systematic mini-review. The abstract does not say the evidence is mostly laboratory studies, so the note's "evidence mostly from laboratory studies" is unchecked. Full text is saved (no Methods section, just the section headings); the body has not been read against the note.

### 8.11 WHO 2023, No level of alcohol consumption is safe (Ch15, "Is zero alcohol…", cited twice) — FIX
- BROKEN LINK: the endnote's URL (who.int/europe/news-room/news/item/04-01-2023-…) returns "404 - File or directory not found". The same release is live at who.int/azerbaijan/news/item/04-01-2023-… (saved as the link).
- The page says "there is no safe amount that does not affect health" and "the risk to the drinker's health starts from the first drop". That is about cancer risk, and sleep is not mentioned.
- A paragraph was amended on 17 September 2026 to correct the description of drinking levels linked to alcohol-attributable cancers ("around half of all alcohol-attributable cancers… occur among people whose alcohol consumption does not meet the definition of heavy drinking"). If the note quotes the earlier wording, re-check it.
- Ask: update the URL, and check what the note quotes against the current text.

### 8.12 SHF, Caffeine, Food, Alcohol, Smoking and Sleep (Ch15 ×3, Ch16 ×2) — mixed
- "Zero alcohol" (Ch15): the page says avoid alcohol "for at least 3-4 hours before bedtime" (summary box: 4 hours). It gives no "zero is safest" statement.
- "Vivid dreams" (Ch15): the page says sleep after drinking is associated with more "nightmares", mostly in the second half of the night. It does not mention vivid dreams or REM rebound.
- "Two to three hours" (Ch16): supported. The summary and body both say "Allow 2-3 hours between the last main meal of the day and going to bed".
- "Hunger raises cortisol" (Ch16): not on the page. It only says "You should not go to bed hungry". The cortisol claim relies on Nakamura 2016 alone.
- The page also says caffeine "can affect your sleep even when consumed 6 hours prior to sleep" and advises avoiding it for at least 4 hours. Neither matches the Ch14 note's wording exactly; check consistency.

### Checked, nothing further to flag in batch 8
- Frontmatter has 12 keys in all ten files. Studies' abstracts and Methods match PubMed and PMC exactly (word count and hash). Web pages match line by line apart from visible-text omissions listed in each file's match_notes.

## Batch 9 (2026-10-17)

### 9.1 Pietilä 2018 (Ch15, "Why does alcohol wake you in the early hours?") — KEEP
- The paper supports the heart-rate and heart-rate-variability sentence: alcohol was linked, dose by dose, to higher sympathetic and lower parasympathetic regulation in the first three hours of sleep, including at low doses.
- It measures heart rhythm, not awakenings. It compares days with and without self-reported alcohol in the same people (4,098 Finnish employees). The note uses it only for the heart-rate point, which matches.

### 9.2 NIAAA, Alcohol Metabolism (Ch15, "Does food slow how quickly alcohol is absorbed?") — FIX
- The saved page does not support the note. It says nothing about food in the stomach, slower absorption, a lower or later blood-alcohol peak, or total alcohol being unchanged. The page covers the enzymes that break alcohol down, acetaldehyde, ketoacidosis and medication interactions. "Absorption" appears only once, about medications; "nutrition" appears once, as a factor in metabolism.
- The claim needs a source that actually says it. I have not filled one from memory.

### 9.3 Westerterp 2004 (Ch16, "Does digesting a meal work against the body's cooling for sleep?") — KEEP?
- Supported: diet-induced thermogenesis is 5–15% of daily energy expenditure on a mixed diet, is higher for protein (20–30% of the energy in the protein) than carbohydrate (5–10%), and is measured over several hours after a meal.
- Not in the paper: body temperature, core temperature or sleep. The note's "and with it body temperature" is the book's inference. The endnote's parenthetical says the effect on pre-sleep cooling was not "measured directly"; more accurately, it was not measured at all.

### 9.4 Enomoto 2026 (Ch16, "Does eating close to bed make sleep worse?") — KEEP
- Matches: 13 young women analysed (14 recruited; one excluded for sleep onset latency over 60 minutes), crossover, dinner 1 h vs 5 h before bed, over 4 days. The 1 h dinner gave lower sleep efficiency, shorter total sleep time, more wake after sleep onset and more arousals.
- Small, and the authors call it a finding "warranting further investigation". The note's wording ("evidence points that way") fits.

### 9.5 Chung 2020 (Ch16, same note) — KEEP?
- Matches: eating within 3 h of bedtime was linked to one or more night awakenings (odds ratio 1.61; 1.43 after adjusting for ethnicity and BMI, 95% CI 1.00–2.04, so the lower bound sits on 1.00). No link with long sleep onset or short sleep duration.
- It is a self-report survey of 793 Sydney university students aged 18–29, run in September 2012. The note calls it one of "large surveys"; it is modest in size.

### 9.6 Yan 2024 (Ch16, same note) — KEEP?
- Matches: later last-meal timing was linked to higher (worse) Pittsburgh Sleep Quality Index scores, as were later first meals and more meal occasions (US NHANES 2005–2008, 7,023 adults, two 24-hour dietary recalls). Cross-sectional, and the analysis did not use the survey weights.
- Effects are small on the PSQI scale and are associations only. The first-meal effect was larger than the last-meal effect, so "later last meals" is a narrow reading.

### 9.7 Nakamura 2016 (Ch16, "Does hunger raise cortisol?") — FIX
- WRONG PAGES in the endnote: it gives 19:30–37; PubMed gives Stress 2016;19(2):151-7. The DOI is right.
- Abstract only is saved (no PMC copy). It confirms fasting strongly raised cortisol, while very-low-calorie and low-calorie diets did not, and the rise faded within weeks. It does not say how long fasts lasted, so the parenthetical "fasting for a day or more" is unchecked here.
- Scope: these are fasting studies, not an evening without a snack. The Sleep Health Foundation page (also cited) only says not to go to bed hungry.

### 9.8 Riley 2024 (Ch16, "Does protein steady overnight blood sugar?") — FIX
- The parenthetical says "in healthy adults". The trial was in adults with prediabetes (BMI 25–45, fasting glucose 100–125 mg/dL), 66 randomised and 51 completed.
- It compared a pistachio snack (57 g) with advice to eat 1–2 carbohydrate exchanges, for 12 weeks each, and measured fasting glucose and other markers, not overnight glucose. Fasting glucose did not differ (0.9 mg/dL, 95% CI −1.2 to 3.1).
- It does not test protein. Pistachios are mostly fat, with some protein and fibre. The note's first sentence ("Protein may help steady overnight blood sugar") has no support in this source.

### 9.9 Afaghi 2007 (Ch16, same note) — KEEP?
- Matches: 12 healthy men; a high-glycaemic-index rice meal 4 h before bed gave a shorter time to fall asleep (9.0 vs 17.5 min) than a low-GI meal, and was better than the same meal 1 h before bed (14.6 min).
- Abstract only. The abstract says carbohydrate raises plasma tryptophan; it does not mention insulin, so "by raising insulin, they help tryptophan… reach the brain" is not in the saved text. Men only, and the authors say relevance to people with sleep problems is unknown.

### 9.10 Edinger 2021, AASM guideline (Ch17, "Does CBT-i make getting out of bed when awake a central recommendation?") — KEEP?
- Supported: the guideline's list of stimulus-control instructions includes "get out of bed when unable to sleep". Stimulus control on its own is a conditional recommendation ("We suggest"), based on low-quality evidence from 8 trials, as the endnote parenthetical says.
- Not in the guideline text: "do something quiet elsewhere" and "return only when sleepy" (it says "go to bed only when sleepy"), and "repeated over weeks". The note's last sentence ("recommended on its own") leaves out the word conditional; the parenthetical carries it.
- The guideline adds that stimulus control may need adapting for people at high risk of falls, with mobility problems, or taking sedative-hypnotics.

### Checked, nothing further to flag in batch 9
- Frontmatter has 12 keys in all ten files. Studies' abstracts and Methods match PubMed and PMC exactly (word count and hash). Pages match the live page the same way (NIAAA whole page; Edinger abstract against PubMed, the rest against PMC).

## Batch 10 (2026-10-17)

### 10.1 Dressle & Riemann 2023 (Ch17, "Does lying awake frustrated keep you awake?") — KEEP?
- Supported: the abstract treats cognitive-emotional hyperarousal as central to insomnia.
- Partly supported: the abstract says there is no conclusive evidence for heart rate and heart-rate variability, and points instead to neuroendocrine and cortical-arousal variables. "Body kept alert" is only partly backed by it.
- Abstract only is saved (Wiley page not tried).

### 10.2 Salari 2020 (Ch17, "What does ACT-i add…") — KEEP?
- Supported: a review of 19 intervention studies (1,577 people) concluding that ACT has a significant effect on insomnia and sleep quality.
- The saved text does not say ACT "teaches people to accept being awake". The abstract describes ACT as enhancing thought flexibility with mindfulness. Studies were screened with a CONSORT quality cutoff of 18, and the abstract states no meta-analysis.

### 10.3 Zeitzer, Phillips, Bauducco (Ch17, "Where do the lux figures in this footnote come from?") — FIX
- Phillips 2019 supports the group ED50 of 24.60 lux, an individual ED50 range of 6 to 350 lux, and melatonin onset delays of 22, 77 and 109 min at 10, 30 and 50 lux.
- Zeitzer 2000 gives a half-maximal response near 100 lux (about 1% of 9,000 lux). It does not support "ED50 across study populations is approximately 24–25 lux"; that figure is Phillips alone.
- The TV at 3 m (~5 lux) and phone (~25–50 lux) figures are not in any saved source; they look like the note's own illustrations.
- Bauducco 2024 (abstract only) is a theoretical review of technology and sleep and has no lux figures.

### 10.4 Chang 2015 (Ch17, "How much does screen light delay sleep?"; also Ch23) — KEEP
- Matches: 12 adults; sleep onset took 25.65 vs 15.75 min (nearly 10 min longer, P=0.009); REM 109.04 vs 120.86 min (P=0.03); lower next-morning alertness. The Methods say about 4 h of reading on 5 evenings, matching "four hours".

### 10.5 Brown 2022 (Ch18, "Light during the day" notes) — KEEP?
- Supported: melanopic EDI of at least 250 lux at the eye in the daytime, 10 lux or less from 3 h before bed, 1 lux or less at night. The paper also says typical working-day melanopic EDI is below 200 lux and existing indoor standards are well below the outdoor light environment.
- Not found: "overcast". The claims that morning light is the strongest cue and shifts the clock earlier are not in the copied sections (the scientific rationale text was not copied, so check there).

### 10.6 Brown 2022 (Ch18, "Does morning movement…") — FIX
- A search of the full text found no mention of morning exercise or movement. Nothing in this source backs the note.
- The note's wording also refers to "the book's framing", unlike the other notes.

### 10.7 NCCIH (Ch18, "Can a light-therapy lamp…") — FIX
- The page has nothing on light therapy. The only mention of bright light is advice to avoid bright artificial light near bedtime.

### 10.8 NCCIH (Ch22, "Do yoga and tai chi help sleep?") — KEEP?
- Supported: the 2019 VA/DoD guideline found insufficient evidence for yoga or tai chi for insomnia. Reviews suggest yoga helps sleep quality, not necessarily insomnia (2020: 19 studies, 1,832 participants; 2019: 4 studies, 353 older adults; 2022: 3 studies, 109 people with rheumatic disease). A 2022 tai chi review (5 studies, 742 participants) suggests better sleep quality, especially in older adults. "Small studies" fits.
- The note's cortisol sentence relies on Hill 2008, not NCCIH. Page last updated May 2024.

### 10.9 Faust 2020 (Ch19, "Does going to bed later than usual affect the next day?") — FIX
- Supported: 255,736 nights, 557 college students, observational. Bedtime 30 min later was linked to higher resting heart rate through sleep (+0.18 bpm, 95% CI 0.11–0.26), persisting into the next day, and the effect grows with the deviation.
- Not supported: "Going to bed earlier than usual did not show the same cost." Bedtimes at least 1 hour earlier also gave significantly higher resting heart rate through sleep. They converged with the normal rate by the end of sleep and did not extend into the next day, so only the next-day cost differs.

### 10.10 Lehrer & Gevirtz 2014 (Ch20, HRV biofeedback) — KEEP?
- This is a mechanisms review, not a review of trials. The best-supported mechanism is strengthened baroreflex homeostasis. The authors say HRV biofeedback has support for several conditions including insomnia, but few areas have extensive controlled-study support.
- "After weeks to months of practice" is not found in the PMC text. The only training detail is a 4-session HRVB vs EMG study (12 vs 13 participants).
- The note's second source (Rusch 2019) is a different source, not in this batch.

### Checked, nothing further to flag in batch 10
- Frontmatter has 12 keys in all ten files. Abstracts and Methods match PubMed and PMC exactly (word count and hash); NCCIH and Brown sections match their pages. Equations and tables do not come through in the Methods (Salari, Zeitzer, Phillips); this is noted in each file. No broken links.

## Batch 11 (2026-10-17)

### 11.1 Rusch 2019 (Ch20, "Does regular meditation or slow breathing train the calming system?") — KEEP?
- Matches: 18 trials, 1,654 people, and a moderate-strength benefit for sleep quality over nonspecific active controls (ES 0.33 at post-treatment, 0.54 at follow-up).
- "Performed comparably to established sleep treatments" rests on low-strength evidence of no difference from specific active controls (ES 0.03 and −0.14, with wide confidence intervals, −0.43 to 0.49 and −0.62 to 0.34). The authors call the findings preliminary.
- The review measures sleep quality in people with clinically significant sleep disturbance. It does not test whether meditation "trains the calming system"; that part of the note rests on Lehrer 2014 (batch 10).

### 11.2 Russo 2017 (Ch20, four notes: vagus nerve, regular breathing practice, nasal breathing, longer exhale) — KEEP?
- The abstract supports effects of slow breathing (4–10 breaths per min in the review's definition) on heart rate variability, respiratory sinus arrhythmia, baroreflex sensitivity and sympathovagal balance in healthy people. It also says more research is needed.
- Only the abstract and the review-methods text are saved, so these claims are unchecked against the body: that the vagus is the "main pathway" of the calming system, that a slow exhale shifts the system toward it, that nasal breathing has higher airway resistance and slows the breath, and that lengthening the exhale gives more of each breath to the slowing phase.
- The "train the vagus nerve" note says itself that the cortisol step "has not been directly demonstrated"; nothing in the saved text covers it.
- OPEN: if you want these four notes checked, the full text is available in PMC (PMC5709795).

### 11.3 Berthoud & Neuhuber 2000 (Ch20, "Does slow breathing work through the vagus nerve?") — KEEP?
- Abstract only is saved. It describes which organs vagal afferent fibres supply and what they sense. It gives no proportion of afferent fibres, so "about four-fifths of vagal fibres carry signals from body to brain" and "most of the vagus nerve's fibres carry information up to the brain" are not in the saved text.
- Nothing in the abstract links the vagus to breathing or attention to bodily sensations.

### 11.4 Akimoto 2018 (Ch20, "Does the 528 Hz frequency itself aid sleep?") — KEEP?
- Matches: crossover, 9 healthy adults (1 man, 8 women), a single 5-minute exposure. After 528 Hz music cortisol fell and oxytocin rose significantly; no significant change in any salivary marker after 440 Hz. The note's cautions (tiny sample, single session, preliminary) are accurate.
- The paper compares before and after within each condition (Wilcoxon signed-rank tests); it does not report a direct 528 Hz vs 440 Hz test. "Compared with 440 Hz" is a fair reading of the pattern, but not a tested difference.
- The study measured stress markers and mood, not sleep. Its "528 Hz music" is piano music tuned with a 444 Hz reference, and the paper itself says the effects ascribed to solfeggio frequencies have no scientific basis.

### 11.5 Sleep Foundation (US) (Ch21, "When is it too late in the day to nap?") — FIX
- Date: the page shows "Updated June 22, 2026"; the endnote says "rev. 2025".
- Matches: the page says "most experts recommend avoiding naps after 3 p.m." and "limiting your nap to at least eight hours before bedtime" (the page's wording, which reads oddly).
- The note's lead sentence says standard guidance is to avoid naps "within 7–8 hours of bedtime". Seven hours is not on any of the three pages saved for this note (Sleep Foundation, Sleep Health Foundation, Mayo Clinic).

### 11.6 Mayo Clinic (Ch21, same note) — KEEP?
- The page says napping after 3 p.m. can make it harder to sleep soundly at night, and a 20- to 30-minute nap is ideal. "Mayo Clinic aligns with this" holds for the 3 p.m. point only; it gives no hours-before-bedtime figure.
- The page is dated Nov. 06, 2024 and could be added to the source line.

### 11.7 Sleep Health Foundation (AU) (Ch21, same note and "Do naps use up the sleep pressure you need for the night?") — FIX
- First note: "endorses a 15–30 minute optimal nap duration" matches ("it is best to nap for 15-30 minutes").
- Second note: this page is the only source cited, and it does not support the mechanism. It does not use the term sleep pressure, does not say a nap clears pressure that built up since waking, and says nothing about a short early nap having little effect. It says only that long naps, and naps too late in the day, can make it harder to sleep or fall asleep at the usual time.
- The Sleep Foundation (US) page does say daytime napping "reduces your sleep drive", and lists Tarokh et al. 2021 (naps not as effective as night sleep at dissipating sleep pressure) in its references. Either could be cited for the mechanism.
- The page is dated January 12, 2024.

### 11.8 De Nys 2022 (Ch22, "Does regular exercise lower cortisol and improve sleep quality?") — KEEP?
- Matches the numbers: SMD −0.37 for cortisol and −0.30 for sleep quality. Ten studies, mostly breast cancer patients, as the note says.
- The abstract grades the evidence as moderate-certainty for cortisol and low-certainty for sleep quality, and says there were few males and no older adults. "The book's claim is well supported" is stronger than a low-certainty result on sleep.
- The last sentence ("consistent with the broader exercise-physiology literature") has no source in this note.
- Abstract only (the publisher page showed a robot check).

### 11.9 Leota 2025 (Ch22, "How close to bedtime can you exercise vigorously?") — KEEP
- Matches: 14,689 people, 4,084,354 person-nights; exercise ending at least 4 hours before sleep onset showed no association with changes in sleep regardless of strain; later timing and higher strain were linked to delayed onset, shorter sleep, lower quality, higher nocturnal resting heart rate and lower nocturnal heart rate variability.
- Context for the note: a retrospective cohort of physically active wearable users, so associations only. The authors also suggest lighter-strain exercise within the 4-hour window as an option, which the note does not mention.

### 11.10 Stutz 2019 (Ch22, same note) — KEEP?
- The abstract (23 studies, healthy adults, a single evening session) concludes the studies "do not support the hypothesis that evening exercise negatively affects sleep, in fact rather the opposite", with possible impairment of sleep-onset latency, total sleep time and sleep efficiency only after vigorous exercise ending 1 hour or less before bedtime. Its moderator effects disappeared after removing one study.
- The note says "Research supports four hours as the evidence-based threshold" and does not mention that this review found no overall harm and a 1-hour window. The two sources point to different thresholds.
- Abstract only (Springer shows only the abstract unless the article is bought).

### Checked, nothing further to flag in batch 11
- Frontmatter has 12 keys in all ten files. Abstracts match PubMed (word count and hash); Methods match PMC for Rusch, Russo and Leota, and the Akimoto page; the three web pages match their live pages (Relevant text and Basis). Tables and figures do not come through in the Methods (Rusch, Leota, Akimoto); this is noted in each file. No broken links. Two files are abstract only because of a robot check (De Nys) or a paywall (Stutz); Berthoud has no PMC copy.

## Batch 12 (2026-10-17)

### 12.1 Hartstein 2024 (Ch23, "Does screen content matter more than screen light for delaying sleep?") — KEEP?
- Matches: the panel reached consensus that the content of presleep screen use impairs sleep health in children and adolescents, and did NOT reach consensus on the light from presleep screen use for any age group. Blue-light-filtering interventions "consistently showed only minimal improvements".
- Not matched: the note says the panel "agreed that stimulating pre-bed screen content harms sleep". The statement voted on was "the content of presleep screen use impairs sleep health", for children and adolescents only. There was no consensus for adults on any statement. "Stimulating" appears only in the Discussion's closing advice (avoid highly stimulating and interactive content in the wind-down window).
- "Matter more than" was not a statement the panel voted on, so "On current evidence, yes" is the note's inference. The source line says the statement is "focused on children and adolescents", but the note's text does not.
- The Discussion also says several seminal adult studies did report light effects, while the panel found other studies inconsistent. Chang 2015 (batch 10) is one of those adult laboratory studies.

### 12.2 Soroka 2019 (Ch23, "Do people react most strongly to provocative content?") — KEEP?
- Matches: 17 countries, 6 continents, stronger physiological reactions to negative than positive news on average.
- The study compared negative with positive news tone, not "provocative" content as such. The paper also stresses considerable individual variation.
- The source line says heart rate; the paper used heart-rate variability (RMSSD) from blood volume pulse, plus skin conductance. The main text says the shift in skin conductance was about 65% of one standard deviation, and the RMSSD difference about 10% of one.

### 12.3 Zaplatosch & Adams 2020 (Ch24, "Does mild dehydration raise cortisol?") — KEEP?
- Matches: cortisol significantly elevated with hypohydration (SMD 1.12, 95% CI 0.583 to 1.67). The note's own caveat (everyday mild dehydration is an extension) is fair.
- "Across 21 studies": the abstract says 21 articles were eligible for the whole review (cortisol was one of several markers), and does not say how many fed the cortisol result.
- The abstract concludes acute hypohydration has "a negligible effect on markers of glycemic regulation, appetite, anabolism and stress", while cortisol (a catabolism marker in its framing) rose. The review induced dehydration by measured body mass loss (fluid restriction, diuretics, heat, exercise); the saved text does not say what size of loss counts as mild.

### 12.4 Sawka 2007, ACSM position stand (Ch24, "Does dehydration make it harder for the body to cool?") — OPEN
- Abstract only (full text is subscription only). The abstract covers fluid replacement before, during and after exercise, and names a loss of more than 2% of body weight as the level to avoid. It says nothing about sweating, skin blood flow or core temperature, so the note's claim is unchecked here.

### 12.5 George 1975 (Ch24, "Does cortisol make the bladder signal louder during lighter sleep?") — FIX
- Authors: PubMed lists six authors (the last "M Kuchel Orofo-Oftega"); the endnote lists seven (…Boucher R, Kuchel O, Rojo-Ortega JM). Check against the paper.
- Matches: plasma vasopressin was higher at night than by day (8 of 10 cycles, 8 healthy men), and "a rise in PAV explains, to some extent, the known nocturnal decrease in urine output". The abstract says the peak occurred "at 2400 or 3400 h" (likely a typing error); the note says midnight to 4 a.m.
- The abstract reports that dexamethasone (a glucocorticoid) did not change the pattern and lowered vasopressin. It says nothing about cortisol raising the bladder signal, lighter sleep or arousal. The note itself says that mechanism "has not been directly demonstrated".

### 12.6 Andersson & Van Kerrebroeck 2018 (Ch24, same note) — FIX
- The PMC text has no mention of cortisol, arousal or midnight. It is a review of drugs for nocturia, which lists sleep disorders and circadian clock disorders among the causes, and discusses desmopressin. It does not support the "lighter sleep lowers the arousal threshold" or cortisol steps of the note.

### 12.7 NHS inform (Ch24, "Can you rely on thirst, and what does urine colour tell you?") — FIX
- The page lists thirst among "other symptoms of dehydration". It does not say thirst lags behind need, or that waiting until thirsty means falling behind.
- Urine colour: it gives a chart (1–3 "healthy pee", 4–8 "drink more") and says dark, strong-smelling urine is a clear sign you need more fluid. It does not use "pale straw" or "dark yellow". The page shows no date.

### 12.8 EFSA 2010 (Ch24, "Is around two litres a day a sensible target?") — KEEP?
- Matches: adequate intakes of 2.0 L/day for women and 2.5 L/day for men, as total water including food moisture, for moderate temperature and activity (PAL 1.6).
- The abstract does not give the share from food ("roughly a fifth") or a figure for drinking alone (1.5 to 2 litres); those are unchecked. The note's last sentence (needs rise with heat and activity) fits the abstract's stated limits. Abstract only; the full opinion is a PDF download.

### 12.9 Spiegel 2004 (Ch25, "Does poor sleep make you hungrier, especially for sweet food?") — KEEP?
- Matches: 12 healthy young men; leptin down 18%, ghrelin up 28%, hunger up 24%, appetite up 23%, most for calorie-dense, high-carbohydrate foods (33% to 45%).
- The abstract says "2 days of sleep restriction and 2 days of sleep extension"; the source line's "four hours in bed vs ten" is not in the abstract. The abstract says "associated with", in a crossover; it does not say sweets in particular, but high-carbohydrate calorie-dense food. The authors list the small, male-only sample as a limitation. Abstract only.

### 12.10 Malik 2008 (Ch25, same note) — KEEP?
- Matches: intravenous ghrelin in healthy volunteers during scanning increased the brain response to food pictures in the amygdala, orbitofrontal cortex, anterior insula and striatum, correlated with hunger ratings.
- The study did not involve sleep. The note's "Ghrelin also acts on the brain's reward system" is supported; the link from poor sleep to this effect rests on Spiegel's ghrelin rise. Abstract only.

### Checked, nothing further to flag in batch 12
- Frontmatter has 12 keys in all ten files. Abstracts match PubMed (word count and hash); Methods, Results and Discussion match PMC (Hartstein, Soroka, Zaplatosch); NHS inform and EFSA match the live pages. Tables and figures do not come through (Hartstein Table 1 and the figures). Abstract only because no free full text: ACSM (subscription), EFSA (PDF only), George, Spiegel and Malik (no PMC copy). No broken links. The Wiley bot check did not appear for EFSA on this visit.

## Batch 13 (2026-10-17)

### 13.1 Gonzalez-Bono 2002 (Ch25, "Can a high-sugar diet affect the cortisol system over time?") — KEEP?
- Matches the source line: 37 healthy men fasted at least 8 hours, four groups (glucose n=8, protein n=10, fat n=10, water n=9) one hour before the Trier Social Stress Test; absolute cortisol and net cortisol increase were greater in the glucose group (both P < 0.05), and the cortisol response correlated with blood glucose changes.
- It is a single acute drink in young men, so it does not show an effect "over time". Abstract only (no PMC copy).

### 13.2 Di Polito 2023 (same note) — KEEP?
- Matches: 54 adults aged 18 to 49; higher sugar intake (self-reported over 6 months by a food frequency questionnaire) predicted a weaker cortisol response to a cold pressor test, controlling for BMI and gender.
- Single session, cross-sectional diet data, and a physiological (not psychological) stressor.

### 13.3 Hackett 2014 (same note) — KEEP?
- Matches: type 2 diabetes was associated with a flatter daily cortisol slope (b = 0.004, P = .014) and higher bedtime cortisol (b = 0.063, P = .020) in 3,508 Whitehall II participants (238 with type 2 diabetes), cross-sectional.
- The paper is about diabetes status, not sugar intake. Across the three sources (one acute trial, two cross-sectional studies), none follows people over time, so the note's closing sentence ("the blood-sugar and cortisol systems shape each other over time") goes beyond them.

### 13.4 Stuart 2013 (Ch25, "Can an evening sugar hit cause a 2–3 a.m. wake?") — KEEP?
- A case report of two patients with reactive hypoglycaemia during an extended glucose tolerance test (75 g glucose, samples every 30 minutes for 4 hours). One had symptoms early and one late; the authors speculate on mechanisms and discuss a low-glycaemic-index diet.
- The abstract gives no times for the symptoms, nothing about sleep or night waking, and no evening setting. The note's "two to four hours after eating" is not in the abstract. The note itself says the full chain "has not been demonstrated end-to-end".

### 13.5 Sweatt 2026 (same note) — KEEP?
- The study defines reactive hypoglycemia from glucose curves after a morning liquid meal in 69 non-diabetic adults with obesity (19 classified as RH). Its Methods describe RH as "traditionally" a rapid decline in glucose 2–5 hours after food, and use criteria of a nadir at least 5 mg/dL below fasting before 60 minutes, or a minimum at or below 78 mg/dL within 80 minutes.
- The abstract reports higher insulin sensitivity and higher disposition index in RH, not an "overshoot" of insulin. No sleep measure.
- The endnote gives a Europe PMC address, no page number (the paper is Nutrients 2026;18(5):822) and no title.

### 13.6 Verberne 2014 (same note) — KEEP
- The abstract lists cortisol among the hormones secreted in the counterregulatory response to falling glucose, which matches "the brain triggers a cortisol counter-regulatory response to falling glucose". It is a review of neural pathways; it says nothing on sleep. The note's claim that cortisol "runs higher in the small hours anyway" has no source in this note.

### 13.7 Myszkowska 2021 (Ch25, "Do food sensitivities generate a background immune response?") — FIX
- The source is a study of four women. Its abstract says higher IgG4 levels against foods and higher cytotoxic test values "are not clinically relevant" and "should not be decisive for the elimination of food products". It does not describe a persistent background immune response.
- It supports only the first sentence (non-IgE food hypersensitivity is recognised). The second half of the note (a contested mechanism) is not what this paper argues. The abstract also says elimination diets based on these tests can cause nutritional deficiencies and loss of tolerance.

### 13.8 Minihane 2015 (same note) — KEEP?
- A position paper from ILSI Europe (a 2013 workshop), 17 authors, not a trial. The abstract calls the importance of chronic low-grade inflammation "now clear" and reviews diet composition and inflammatory status, but also says the human data rely on circulating cytokines in the fasting state, "an insensitive and highly variable index". "Established in the literature" is stronger than the abstract.
- It does not mention food sensitivities or intolerance. The first author line in the endnote ("Minihane A-M, Vinoy S et al. (Calder PC)") is unusual; PubMed lists 17 authors, Minihane AM first and Calder PC last.

### 13.9 NHS inform, *Food Intolerance* (Ch25, "Can food sensitivity cause disrupted sleep and brain fog?" and "Are gluten, dairy, eggs, and soy the most common triggers?") — FIX
- NOT FOUND. The cited link is only the home page. The A to Z list and the Nutritional category list Food allergy and Lactose intolerance pages but none called Food intolerance, and the site search was blocked (WAF page). No NHS inform text is saved for this source.
- The Food allergy page mentions milk, eggs, soya and wheat only as childhood food allergies, and says nothing about gluten, sleep or brain fog.
- The "most common triggers" note also cites Harvard Health (not yet saved) and says these foods are among the "FDA's nine major food allergens", which neither cited source is shown to state.
- Please supply the intended address, or replace the citation.

### 13.10 Altinsoy & Dikmen 2025 (Ch25, "Can food sensitivity cause disrupted sleep and brain fog?") — FIX
- The source-line caveat is accurate: cross-sectional; brain fog scores correlated with gastrointestinal symptoms, and gastrointestinal symptoms and mood were the significant predictors (R = 0.599, R2 = 0.358).
- But the Methods exclude people with food allergies and intolerances (for example coeliac disease and lactose intolerance), and the abstract frames brain fog around long COVID. The study does not test food sensitivity as a cause of brain fog or disrupted sleep. Sleep quality correlated negatively with brain fog but was not significant in the regression (p = 0.367). MIND diet adherence was unrelated.

### Checked, nothing further to flag in batch 13
- Frontmatter has 12 keys in all ten files. Abstracts match PubMed (word count and hash); Methods match PMC for Sweatt, Di Polito, Hackett, Stuart, Myszkowska and Altinsoy. Tables, figures and some equations do not come through (Sweatt 2.8.2 has a missing symbol). Verberne and Minihane have no Methods section. Gonzalez-Bono is abstract only (no PMC copy). One source not found (NHS inform). A "Checking your browser" screen on PubMed passed on its own; the NHS inform search page was blocked by a WAF page and not bypassed.

## Batch 14 (2026-10-17)

**14.1 Harvard Health, *Food Allergy vs. Food Intolerance* (S131) — OPEN**
- The cited link is only the Harvard Health home page; no page with that title was found, so nothing is saved (NOT FOUND, LOW). The nearest page found (Campos, Jan 30, 2020, "Food allergy, intolerance, or sensitivity…") does not say wheat, milk, eggs and soy are the most common triggers. The "Are gluten, dairy, eggs, and soy…" note therefore has no saved support from either of its two sources (NHS inform is also NOT FOUND, see 13.9). Give the exact Harvard page, or replace the source.

**14.2 Cleveland Clinic, *Elimination Diet* (S132) — KEEP?**
- The page (April 12, 2022; dietitian Sharon Jaeger quoted) supports "elimination diets are the gold standard" and a four-to-eight-week removal then one-at-a-time reintroduction. It also says to do this only with a healthcare professional.
- The book note says "no blood test replaces it". The page does not say that. It also defines "food sensitivity" as a gut-bacteria imbalance, which is not the usual clinical meaning; the book should not lean on that definition.
- The page lists eight foods as about 90% of food allergies (eggs, fish, milk, peanuts, shellfish, soy, tree nuts, wheat); this is a better source for the "most common triggers" note than the two cited there.

**14.3 Stapel et al. 2008 (S133) — KEEP?**
- Supports "IgG4 testing is irrelevant and should not be performed" almost word for word. The paper is about IgG4, not total IgG; the book note uses "IgG food-sensitivity tests" in the heading and "IgG4" in the text. Abstract only (no PMC copy; Methods NOT FOUND).

**14.4 AAAAI, *The Myth of IgG Food Panel Testing* (S134) — KEEP?**
- The page says no test has been proven for food sensitivities, IgG is likely a normal response to exposure, and AAAAI and the Canadian Society of Allergy and Clinical Immunology recommend against IgG testing. It does not use the exact wording "holds the same position as EAACI", but the position is the same. The page lists the EAACI IgG4 position paper support (2010) as a reference.

### Checked, nothing further to flag in batch 14
- Frontmatter has 12 keys in all four files. Stapel abstract matches PubMed (250 words, hash 1143805207). Cleveland Clinic and AAAAI text match the page text (word count and hash). One source not found (Harvard Health, incomplete link).
