---
source_type: STUDY
source_line: "Brown EN, Choe Y, Shanahan TL, Czeisler CA 1997, *Am J Physiol* 272(3):E506–E516. https://doi.org/10.1152/ajpendo.1997.272.3.E506 (model fitted to plasma melatonin in 18 healthy men kept awake in dim light; melatonin switches on, climbs to a high plateau within a few hours and switches off; model onset correlated 0.93 with DLMO)"
cited_in:
  - none yet (collected in the N4 review, 2026-10-19)
title: "A mathematical model of diurnal variations in human plasma melatonin levels"
authors_or_body: E N Brown, Y Choe, T L Shanahan, C A Czeisler
year: 1997 (Mar)
journal_or_publisher: American Journal of Physiology 272(3 Pt 1):E506–E516
link: https://pubmed.ncbi.nlm.nih.gov/9124558/
link_checked: YES
match_confidence: HIGH
match_notes: N4 review 2026-10-19. PMID 9124558, DOI confirmed on PubMed; full text paywalled. Rise-rate parameters taken from the published CellML implementation (models.cellml.org, Brown Choe Shanahan Czeisler 1997): synthesis rise half-life 24.04 min, clearance half-life 23.67 min, infusion half-life 2.82 min. The share-of-plateau figures below are Claude's own simulation of those median values, not numbers reported in the paper.
access: ABSTRACT ONLY (paywalled)
---

## Abstract

Studies in animals and humans suggest that the diurnal pattern in plasma melatonin levels is due to the hormone's rates of synthesis, circulatory infusion and clearance, circadian control of synthesis onset and offset, environmental lighting conditions, and error in the melatonin immunoassay. A two-dimensional linear differential equation model of the hormone is formulated and is used to analyze plasma melatonin levels in 18 normal healthy male subjects during a constant routine. Recently developed Bayesian statistical procedures are used to incorporate correctly the magnitude of the immunoassay error into the analysis. The estimated parameters [median (range)] were clearance half-life of 23.67 (14.79-59.93) min, synthesis onset time of 2206 (1940-0029), synthesis offset time of 0621 (0246-0817), and maximum N-acetyltransferase activity of 7.17(2.34-17.93) pmol x l(-1) x min(-1). All were in good agreement with values from previous reports. The difference between synthesis offset time and the phase of the core temperature minimum was 1 h 15 min (-4 h 38 min-2 h 43 min). The correlation between synthesis onset and the dim light melatonin onset was 0.93. Our model provides a more physiologically plausible estimate of the melatonin synthesis onset time than that given by the dim light melatonin onset and the first reliable means of estimating the phase of synthesis offset. Our analysis shows that the circadian and pharmacokinetics parameters of melatonin can be reliably estimated from a single model.

## Methods

Not available: full text paywalled.

## Simulation of the published median parameters (Claude, N4 review; not from the paper)

Share of the night's plateau after the 10 pM threshold is crossed: about 60% at +1 h, about 80% at +1.5 h, about 90% at +2 h.

## Written summary (not copied text)

*Written 2026-10-19 from the text saved in this file only, following derived/study-summary-template.md; nothing looked up online. Where the saved text does not give a detail, the summary says so.*

### Melatonin Switches On, Climbs Fast, Then Switches Off

In a 1997 study, researchers built a mathematical model of how melatonin rises and falls in the blood and tested it on 18 healthy men kept awake in dim light under a constant routine. The model treats melatonin as switching on at a set time, being made and cleared at measurable rates, and switching off in the early morning.

For a typical man, melatonin production switched on at about 10 pm and off at about 6:20 am, and melatonin was cleared from the blood with a half-life of about 24 minutes. The modelled switch-on time agreed very closely with the standard dim-light melatonin onset measure.

**The main takeaway:** Melatonin behaves like a switch: it turns on in the late evening, rises quickly to a night-long high, and turns off before dawn.

**Quick facts**

- **Authors:** Brown EN, Choe Y, Shanahan TL, Czeisler CA
- **Link:** https://pubmed.ncbi.nlm.nih.gov/9124558/
- **Published in:** *American Journal of Physiology* (peer-reviewed journal)
- **Study type:** Mathematical modelling of lab data (constant routine)
- **Age range:** Not stated in the saved text
- **Measures:** Plasma melatonin over time; core temperature minimum
- **Caveat:** 18 men only; abstract only. The "share of plateau" figures saved in this file are Claude's own simulation, not results from the paper
- **Replication:** The authors report agreement with earlier values
- **Evidence:** Moderate (good fit, small all-male sample)
