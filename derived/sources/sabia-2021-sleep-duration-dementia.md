---
source_type: STUDY
source_line: "Sabia S et al. 2021, *Nat Commun* 12:2289. https://doi.org/10.1038/s41467-021-22354-2 (about 8,000 UK adults followed for 25 years; six hours or less in one's 50s and 60s linked to about 30% higher dementia risk; observational, so cause and effect is not established)"
cited_in:
  - Chapter 1 — Is poor sleep linked to serious disease?
title: Association of sleep duration in middle and old age with incidence of dementia
authors_or_body: Séverine Sabia, Aurore Fayosse, Julien Dumurgier, Vincent T. van Hees, Claire Paquet, Andrew Sommerlad, Mika Kivimäki, Aline Dugravot, Archana Singh-Manoux
year: 2021 (published 20 April 2021)
journal_or_publisher: Nature Communications, 12:2289
link: https://doi.org/10.1038/s41467-021-22354-2
link_checked: YES
match_confidence: HIGH
match_notes: none. The DOI resolved to https://www.nature.com/articles/s41467-021-22354-2 with this title, first author, journal, volume and article number. Methods copied from the page's Methods section (page text, paragraph breaks kept); the "ref." numbers appear as in the page text with superscripts flattened.
access: FULL TEXT
---

## Abstract

Sleep dysregulation is a feature of dementia but it remains unclear whether sleep duration prior to old age is associated with dementia incidence. Using data from 7959 participants of the Whitehall II study, we examined the association between sleep duration and incidence of dementia (521 diagnosed cases) using a 25-year follow-up. Here we report higher dementia risk associated with a sleep duration of six hours or less at age 50 and 60, compared with a normal (7 h) sleep duration, although this was imprecisely estimated for sleep duration at age 70 (hazard ratios (HR) 1.22 (95% confidence interval 1.01–1.48), 1.37 (1.10–1.72), and 1.24 (0.98–1.57), respectively). Persistent short sleep duration at age 50, 60, and 70 compared to persistent normal sleep duration was also associated with a 30% increased dementia risk independently of sociodemographic, behavioural, cardiometabolic, and mental health factors. These findings suggest that short sleep duration in midlife is associated with an increased risk of late-onset dementia.

## Methods

### Study population

The Whitehall II study is a cohort study that was established among 10,308 British civil servants (33.1% women, age range 35–55) in 1985–1988 (ref. 40). Since baseline, follow-up clinical data collection waves have taken place every 4–5 years with each wave lasting ~2 years, with the last wave conducted in 2015–2016. In addition to clinical examinations in the study, data over the follow-up are obtained via linkage to electronic health records of the UK National Health Service (NHS) for participants recruited to the study. The NHS provides most of the health care in the country, including in- and out-patient care, and record linkage is undertaken using a unique NHS identifier held by all UK residents. Data from linked records were updated on an annual basis, until 31st March 2019. Written, informed consent from participants was obtained at each contact. Research ethics approvals were renewed at each wave; the most recent approval was obtained from the University College London Hospital Committee on the Ethics of Human Research (reference number 85/0938).

### Measures

#### Sleep duration

Sleep duration was assessed by questionnaire in 1985–1988, 1997–1999, 2002–2004, 2007–2009, 2012–2013, and 2015–2016 using the question ‘how many hours of sleep do you have on an average weeknight?’. Response categories were 5 h or less, 6, 7, 8, and 9 h or more. We extracted sleep duration at age 50, 60, and 70 for each participant across the data waves, allowing a ±5-year margin for each age category. In order to allow sufficient number of dementia cases in each sleep category, we pooled categories of sleep duration as follows: short (≤6 h per night), normal (7 h per night), and long (≥8 h per night)41.

Trajectories of change in sleep duration between age 50 and 70 were defined using group-based trajectory modelling using the traj-command in Stata42. Groups were chosen according to model fit statistics (Bayesian Information Criterion values and average posterior probabilities) and meaningful interpretation43. The sleep duration categories in the construction of trajectories were the same as in the main analyses, and were based on participants who were alive and free of dementia at age 70 with at least two out of three measures of sleep duration at age 50, 60, and 70.

The accelerometer substudy was undertaken in 2012–2013 (ref. 44) on study participants who either attended the central London research clinic or were seen at home in those living in the South-Eastern regions of England. These participants were asked to wear a wrist-worn accelerometer, the GENEActiv (Activinsights Ltd, Kimbolton, UK), during nine consecutive days over 24 h. Sleep duration was estimated using a validated algorithm guided by a sleep log and implemented in R (version 3.6.3) package GGIR version 2.0-1 (ref. 45); data from the first and last nights were removed leading to data over 7 nights45. Usual daily sleep duration was estimated as the mean of sleep duration over the 7 nights and for those with <7 days of measurement, weighted average of sleep duration was calculated according to week days and weekend days46. Accelerometer-assessed sleep duration was categorized into tertiles rather than categories used for self-reported sleep as only 167 (six dementia cases) participants had accelerometer-assessed sleep duration of 8 h or more. Study participants were between 60 and 83 years in this sub-study, a one-off addition to the main data collection. Therefore, age-specific analysis as in the self-reported measure of sleep duration was not possible with the accelerometer data.

#### Dementia

Dementia cases were ascertained by linkage to three national registers (the national hospital episode statistics (HES) database, the Mental Health Services Data Set, and the mortality register) up to the 31st of March 2019 using the unique National Health Service (NHS) identification number. Dementia cases were identified based on ICD-10 codes F00-F03, F05.1, G30, and G31. The NHS provides most of the health care, including out- and in-patient care. The sensitivity and specificity of dementia in the NHS HES data is 78.0 and 92.0% (ref. 34). The sensitivity in our study is likely to be higher as we also used data from the Mental Health Services Data Set, a national database that contains information on dementia for persons in contact with mental health services in hospitals, out-patient clinics, and the community47. The first record of dementia diagnosis in any of the three registers was used as date of dementia in the analysis.

#### Covariates

Sociodemographic variables included age, sex, ethnicity (white and non-white), education (lower primary school or less, lower secondary school, higher secondary school diploma, and university), and marital status (married or cohabiting, and other). Health behaviours included cigarette smoking status (never smoker, ex-smoker, and current smoker), alcohol consumption in the previous week (no alcohol in the previous week, 1–14 units per week, and >14 units per week), time spent in moderate and vigorous physical activity, and frequency of fruits and vegetables consumption (less than daily, once a day, and twice or more a day).

Health-related variables included measures of cardiometabolic risk factors and mental health. Cardiometabolic factors were hypertension (systolic ≥140 or diastolic ≥90 mmHg or use of antihypertensive medication), diabetes mellitus (determined by fasting glucose ≥7.0 mmol/L, reported doctor-diagnosed diabetes, use of diabetes medication, or hospital record), body mass index (BMI, categorized as <20, 20–24.9, 25–29.9, and ≥30 kg/m²) based on height and weight assessment at the clinical examination using standard clinical protocols, and cardiovascular disease (including coronary heart disease and stroke identified using linkage to national hospital records). Mental health factors included current depressive symptomatology defined by the four-item depression subscale of the General Health Questionnaire48, and self-reported use of CNS medication (anti-depressant, antipsychotic, hypnotic, anxiolytic, or Parkinson medications).

History of mental disorders before age 65 was assessed based on self-reported use of anti-depressants or linkage to national hospital records and mental health registry based on ICD codes F06, F07, F09, F20–48, and F60–69 (excluding F65 and F66).

### Statistical analysis

Four sets of analyses were undertaken, described below (Fig. 1 for flow chart). All analyses were performed using Cox regression with age as the timescale to model the associations with incident dementia. Participants were included into the analysis if they had data on sleep duration and covariates assessed at the age of interest allowing a ±5-year margin and were free of dementia at this date. Data were censored at date of record of dementia, death, or March 31st 2019, whichever came first. The proportional hazard assumption was verified using Schoenfeld residuals. Analyses were first adjusted for sociodemographic factors, then additionally for health behaviours, and finally for health-related factors.

We first examined the association between sleep duration at age 50, 60, and 70, in separate models, and incident dementia. For these analyses, age of entry was the age at clinical assessment closest to the age of interest from which the sleep duration measure and covariates were drawn.

We examined the association of trajectories of sleep duration, to reflect changes between the age of 50 and 70, with incident dementia with age of entry and covariates drawn from when participants were 70 years.

In order to assess the role of mental disorders in the association of sleep duration with dementia, we repeated the previous analyses, excluding participants with mental disorders before the age of 65. Mental disorders diagnosed after age 65 were not excluded as they could be features of the preclinical period of dementia49.

The final analyses examined the association between objectively assessed sleep duration and incident dementia. Participants were followed from the age at accelerometer assessment, and covariates were drawn from the same wave of data collection. To examine the shape of the association between accelerometer-assessed sleep duration, measured in rich detail, and incidence of dementia we used restricted cubic spline regressions with Harrell knots50, Stata command xblc51, with 7 h as the reference. Then, in further analyses tertiles of accelerometer-assessed sleep duration were used.

We undertook a series of additional/sensitivity analysis. One, we repeated the main analyses using inverse-probability weighting to account for missing data52. This involved first calculating the probability of being included in the analytical sample using logistic regression that included demographic, socioeconomic, behavioural factors, as well as sleep duration at recruitment, morbidities including dementia and mortality over follow-up, and stepwise-selected interactions between covariates. The inverse of these probabilities were used as weights in Cox regression. Two, in a sub-sample of participants with data on APOE genotype, we repeated the main analyses with APOE ε4 (1 or 2, vs 0) as a covariate in the analysis. Three, in order to examine whether observed results apply to dementia due Alzheimer’s disease, we repeated the analyses using a proxy definition of this outcome. This consisted of defining Alzheimer’s disease dementia as dementia cases free of cardiovascular disease (stroke or myocardial infarction)53 over the follow-up. Analyses 2 and 3 were exploratory and due to smaller numbers in analysis the direction of results rather than statistical significance should be given more importance. All analyses were performed using STATA version 16.1 (StataCorp). A two-sided P value ≤ 0.05 was considered statistically significant. STROBE statement is available in the online Supplement.

### Reporting summary

Further information on research design is available in the Nature Research Reporting Summary linked to this article.

## Written summary (not copied text)

*Written 2026-10-19 from the text saved in this file only, following derived/study-summary-template.md; nothing looked up online. Where the saved text does not give a detail, the summary says so.*

### Short Sleep in Midlife Linked to Higher Dementia Risk

In a 2021 analysis of the Whitehall II study of British civil servants, researchers followed 7,959 people for 25 years, using questionnaire answers on weeknight sleep collected repeatedly from 1985 to 2016 and health records to identify 521 dementia cases.

Sleeping six hours or less at age 50 or 60, compared with seven hours, was linked to a higher dementia risk later; the link at age 70 was less certain. People who consistently slept six hours or less at 50, 60 and 70 had about a 30% higher risk than consistent seven-hour sleepers, even after allowing for many social, health and mental-health factors.

**The main takeaway:** Regularly sleeping six hours or less in your 50s and 60s is linked to a higher risk of dementia later, though this study can't prove short sleep causes it.

**Quick facts**

- **Authors:** Sabia S, Fayosse A, Dumurgier J, van Hees VT, Paquet C, Sommerlad A, Kivimäki M, Dugravot A, Singh-Manoux A
- **Link:** https://doi.org/10.1038/s41467-021-22354-2
- **Published in:** *Nature Communications* (peer-reviewed journal)
- **Study type:** Prospective cohort study
- **Age range:** Followed from midlife (35–55 at study start) into old age
- **Measures:** Self-reported weeknight sleep duration; dementia from health records
- **Caveat:** Observational; self-reported sleep; civil-service cohort
- **Replication:** Not checked (saved text only)
- **Evidence:** Moderate (large, long follow-up; association only)
