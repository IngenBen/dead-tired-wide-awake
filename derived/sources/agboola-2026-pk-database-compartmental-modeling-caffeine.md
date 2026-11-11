---
source_type: STUDY
source_line: Agboola OE et al. 2026, *Curr Ther Res Clin Exp* 104:100832. https://doi.org/10.1016/j.curtheres.2026.100832
cited_in:
  - Chapter 14 — What is caffeine's actual half-life?
title: Integration of Clinical Pharmacokinetic Database With Compartmental Modeling and Regulatory Data Analysis
authors_or_body: Oluwaseun E Agboola, Samuel S Agboola, Anuoluwapo Bukola Shaleye, Aniefon Samuel Umoekam, Zainab A Ayinla, Temitope Yinka Olasehinde
year: 2026
journal_or_publisher: Current Therapeutic Research, Clinical and Experimental 104:100832
link: https://pmc.ncbi.nlm.nih.gov/articles/PMC13218119/
link_checked: YES
match_confidence: HIGH
match_notes: Found by searching PubMed for the DOI (10.1016/j.curtheres.2026.100832), PMID 42221553; first author, year, journal, volume and article number match. The DOI link itself was not loaded. The PMC ID was found with the PMC ID converter. The abstract is as printed on PubMed (one block, with "Methods" inline). Methods are copied from the free PMC page, section "Methodology" (sub-headings kept). The one-compartment equation in the "Compartmental Pharmacokinetic Modeling" section is typeset on the page and does not come through as text; the sentences before and after it are copied. See endnote-review-log.md for how the full text compares with the endnote.
access: FULL TEXT
---

## Abstract

Background: Computational pharmacokinetics increasingly relies on real-world clinical data rather than theoretical simulations. This study integrated authentic patient measurements from PK-DB clinical trials with FDA regulatory databases to characterize drug disposition patterns. Methods: Concentration-time profiles from 75 patients receiving caffeine (100-400 mg, n = 37) or paracetamol (500-1000 mg, n = 38) were analyzed using noncompartmental and one-compartment modeling approaches. FDA regulatory API queries provided contextual regulatory information. Parameters were estimated by a nonlinear least squares optimization of actual clinical measurements.

Results: Caffeine exhibited dose-linear kinetics with apparent oral clearance of 2.96 L/h and a 4.0-hour elimination half-life. Paracetamol's elimination was faster (t½ 1.8 h) with an apparent oral clearance of 14.29 L/h. One-compartment models fit patient data excellently (R² > 0.98; AAFE 1.08-1.50 for all doses). The correlation between dose and AUC reached an impressive r = 0.9997 for caffeine, which was a confirmation of linear pharmacokinetics. The parameters derived from the models were in agreement with published population studies; thus, the approach was validated.

Conclusions: The combination of curated clinical databases along with empirical compartmental modeling leads to the derivation of pharmacokinetically interpretable parameters that are based on actual measurements. This framework allows for evidence-based dose optimization and is applicable to more than 150 compounds in PK-DB, thus providing a significant advantage over simulation-dependent methodologies in translational pharmacometrics.

## Methods

### Clinical Database Access and Data Extraction

Real patient pharmacokinetic data were retrieved from PK-DB (https://pk-db.com), an open-access database of clinical pharmacokinetic studies.27 PK-DB collects concentration-time data from published clinical trials and gives standardized formats with subject numbers, dose levels, sampling times, mean concentrations, and standard errors.28 The database was accessed in December 2025 to retrieve the most current available studies. Prior to analysis, data were screened for duplicate entries by cross-checking study identifiers, dose levels, and concentration-time profiles; no duplicate records were identified in the extracted datasets.

There were 3 doses (100, 200, and 400 mg) with the entire concentration-time profiles from clinical bioavailability studies that were found for caffeine.29 The data consisted of 37 subjects in total from different studies with 48 hours of sampling after the dose. For paracetamol (acetaminophen), 38 subjects' data of 2 doses (500 and 1000 mg) were picked with 24 hours of sampling.30

All concentration values represent mean plasma measurements (mg/L) with associated standard errors reflecting inter-individual variability within study populations.31 Sampling time points varied by dose and drug but typically included early frequent sampling (0.25-2 hours) to characterize absorption and less frequent later sampling (4-48 hours) for elimination characterization.32

### FDA Regulatory Database Integration

Current regulatory information was obtained via the openFDA API (https://api.fda.gov/drug/label.json) using the Python requests library version 2.28.0.33 Queries targeted drug labels using generic names as search parameters with 10-second timeout limits.34 The retrieved data contained various useful information, such as brand names, routes of administration, manufacturers, and the current approval status of different products.35 The API calls were conducted in real-time during the execution of the analysis (December 2025) to ensure the accuracy of the data being used was contemporaneous.36

### Noncompartmental Pharmacokinetic Analysis

Noncompartmental analysis was done on the actual patient concentration-time data without any presumption of particular disposition models.37 The maximum plasma concentration (Cmax) and the maximum concentration time (Tmax) were directly determined through the observed data points' inspection.38 The area under the concentration-time curve from time zero to the last measurable concentration (AUC₀₋last) was computed using the linear trapezoidal rule via the scipy.integrate.trapz function.39

The terminal elimination rate constant (λz) was computed through log-linear regression of the terminal concentration phase, which usually includes the last 50% of the data points where the concentrations are above the quantification limits.40 The elimination half-life is calculated as t½ = ln(2)/λz.41 The area under the curve extrapolated to infinity (AUC₀₋∞) was determined as AUC₀₋last + Clast/λz, where Clast is the last measurable concentration.42

### Compartmental Pharmacokinetic Modeling

The study of the drug's behavior in the body was carried out using a compartmental model.43 The one-compartment model with first-order absorption and elimination was applied to the actual patient data by the following equation44:

where C(t) is the plasma concentration at time t, ka is the absorption rate constant (h⁻¹), ke is the elimination rate constant (h⁻¹), V is the apparent volume of distribution (L), and Dose is the administered quantity (mg).45 When ka and ke are equal, the formula can be expressed as C(t) = (Dose/V) × ka × t × e⁻⁽ᵏᵉ ˣ ᵗ⁾.46

Parameter estimation based on clinical data was done using the method of nonlinear least squares optimization (scipy.optimize.curve_fit), which finds the parameter values that minimize the sum of squared differences between measured plasma levels and model predictions.47 The parameter values were initially guessed as ka = 1.5 h⁻¹, ke = 0.15 h⁻¹, and V = 50 L, taking into account the physiological plausibility.48 Parameter bounds constrained solutions to biologically meaningful ranges: ka (0.1-10 h⁻¹), ke (0.01-2 h⁻¹), and V (10-200 L).49

Optimization employed a trust region reflective algorithm with a maximum of 5000 function evaluations.50 Clearance was obtained through the formula CL = ke × V.51 The quality of the fit was assessed by the coefficient of determination (R²), root mean square error (RMSE), average fold error (AFE = 10^(mean(log10(predicted/observed)))), and absolute average fold error (AAFE = 10^(mean(|log10(predicted/observed)|))), where AFE values near 1.0 and AAFE values approaching 1.0 indicate accurate predictions.52 The Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) were calculated to support model selection. The standard errors of the parameters were obtained from the elements of the covariance matrix diagonally.53

### Dose-Response Analysis

Dose proportionality was assessed through the application of linear regression on pharmacokinetic parameters (AUC, Cmax) against the administered dose by means of scipy.stats.linregress.54 The correlation coefficients (Pearson r) were used to assess the strength of the linear relationships.55 The threshold of α = 0.05 was applied for testing the significance of the findings.56 The dose-normalized parameters (dose-corrected AUC and Cmax) were then compared across the different dose levels in order to spot any nonproportionality.57

### Statistical Procedures

All statistical analyses employed SciPy version 1.7.0 functions.58 Correlation analyses used scipy.stats.pearsonr for parametric assessment.59 Linear regression slope, intercept, correlation coefficient, p-value, and standard error were computed via scipy.stats.linregress.60 Confidence intervals (95%) were calculated using standard formulas with t-distribution critical values.61

### Data Visualization

Publication-quality figures were generated using matplotlib 3.5.1 and seaborn 0.11.2.62 Every figure was set to have a resolution of 300 dots per inch and to be saved in PNG format.63 The error bars in the concentration-time plots show the standard errors taken from the clinical studies reported in PK-DB.64 The precise arrangement of the multi-panel layouts was done using the matplotlib.gridspec, and it was easy to follow the color schemes that were based on ColorBrewer palettes, which had the accessibility of being colorblind-friendly.65

### Software Environment

The complete analysis was performed using Python 3.8.10 on the operating system Ubuntu 20.04 LTS.66 NumPy 1.21.0 was used as the core library for array operations, pandas 1.3.0 for manipulating data, and finally, Matplotlib/Seaborn for making data visualizations.67 For API interactions, the requests library 2.28.0 was used along with JSON parsing for structured data extraction.68 The effectiveness of the code was improved by using vectorized NumPy operations.69

### Data Transparency and Reproducibility

All of the data regarding concentrations over time was taken from the Algorithmic PK-DB public database, and it can still be found at https://pk-db.com.70 The FDA regulatory information was obtained through public API endpoints (https://api.fda.gov).71 There were no proprietary or restricted datasets used in the study.72 Sample sizes with standard errors and study identifiers are reported honestly.73 The analysis involved no human subjects research and required no ethical approval.74

## Written summary (not copied text)

*Written 2026-10-19 from the text saved in this file only, following derived/study-summary-template.md; nothing looked up online. Where the saved text does not give a detail, the summary says so.*

### Caffeine's Half-Life Is About Four Hours

In a 2026 analysis, researchers took published blood-level data from 37 people given 100, 200 or 400 mg of caffeine (and 38 given paracetamol) from an open clinical database, PK-DB, and fitted a standard model of how the body absorbs and clears a drug. No new volunteers were tested; the data came from earlier clinical studies, with blood sampled for up to 48 hours after the caffeine dose.

Caffeine was cleared at a steady rate whatever the dose, with a half-life of 4.0 hours, meaning about half of a dose is still in the blood four hours later. Doubling the dose doubled the total exposure almost exactly. The figures agreed with earlier population studies.

**The main takeaway:** On average, half the caffeine from a cup is still circulating about four hours later, and the more you take, the proportionally more stays in your system.

**Quick facts**

- **Authors:** Agboola OE, Agboola SS, Shaleye AB, Umoekam AS, Ayinla ZA, Olasehinde TY
- **Link:** https://pmc.ncbi.nlm.nih.gov/articles/PMC13218119/
- **Published in:** *Current Therapeutic Research, Clinical and Experimental* (peer-reviewed journal)
- **Study type:** Pharmacokinetic modelling of pooled published data
- **Age range:** Not stated in the saved text
- **Measures:** Plasma caffeine concentration over time; half-life, clearance, peak level
- **Caveat:** Uses group mean concentrations, so it shows the average, not the wide person-to-person range; no new participants
- **Replication:** The authors report agreement with published population studies
- **Evidence:** Moderate (consistent with prior data, but averaged secondary data)
