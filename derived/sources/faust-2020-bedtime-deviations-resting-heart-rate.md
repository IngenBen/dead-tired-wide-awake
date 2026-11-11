---
source_type: STUDY
source_line: Faust L et al. 2020, *npj Digit Med* 3:39. https://doi.org/10.1038/s41746-020-0250-6 (557 university students, over 255,000 nights of Fitbit data; observational; the effect per night is small)
cited_in:
  - Chapter 19 — Does going to bed later than usual affect the next day?
title: "Deviations from normal bedtimes are associated with short-term increases in resting heart rate"
authors_or_body: Louis Faust, Keith Feldman, Stephen M Mattingly, David Hachen, Nitesh V Chawla
year: 2020
journal_or_publisher: npj Digital Medicine 3:39
link: https://pmc.ncbi.nlm.nih.gov/articles/PMC7090013/
link_checked: YES
match_confidence: HIGH
match_notes: The cited DOI was looked up in PubMed ([doi] search) and returned exactly one record (PMID 32219180) with this title; the PMC full text (PMC7090013) loaded and shows the same title and journal citation. The endnote gives no title. In this paper the Methods section comes after the Discussion. It is copied below from the PMC page, "Methods" section (sub-headings kept), including the captions of Figs. 3, 4 and 5 that sit inside it. The figures themselves are images and do not come through. Methods refer to Supplementary Methods 2, which is not copied.
access: FULL TEXT
---

## Abstract

Despite proper sleep hygiene being critical to our health, guidelines for improving sleep habits often focus on only a single component, namely, sleep duration. Recent works, however, have brought to light the importance of another aspect of sleep: bedtime regularity, given its ties to cognitive and metabolic health outcomes. To further our understanding of this often-neglected component of sleep, the objective of this work was to investigate the association between bedtime regularity and resting heart rate (RHR): an important biomarker for cardiovascular health. Utilizing Fitbit Charge HRs to measure bedtimes, sleep and RHR, 255,736 nights of data were collected from a cohort of 557 college students. We observed that going to bed even 30 minutes later than one's normal bedtime was associated with a significantly higher RHR throughout sleep (Coeff +0.18; 95% CI: +0.11, +0.26 bpm), persisting into the following day and converging with one's normal RHR in the early evening. Bedtimes of at least 1 hour earlier were also associated with significantly higher RHRs throughout sleep; however, they converged with one's normal rate by the end of the sleep session, not extending into the following day. These observations stress the importance of maintaining proper sleep habits, beyond sleep duration, as high variability in bedtimes may be detrimental to one's cardiovascular health.

## Methods

### Study objectives

To address the research questions outlined in the introduction of this manuscript, we utilized a data set comprised of 255,736 nights of sleep across 557 participants. Sleep and HR data were measured utilizing Fitbit Charge HRs, providing highly granular measurements of RHR and reasonable estimates of sleep duration27. The minimally invasive nature of these sensors allowed us to capture uninterrupted streams of participants RHR: providing measures across an individual’s entire night’s sleep and throughout the following day. This continuity allowed for a comprehensive study around not only how RHR may change following bedtime deviations, but also the average time window needed for RHR to return to baseline.

### NetHealth study

The data utilized in this manuscript come from the NetHealth study conducted at the University of Notre Dame. The study followed college students for up to 4 years, beginning the data collection in the summer of 2015 and ending in May of 2019. The most recent snapshot of the data, however, included data only up to the Fall 2019 semester. Data collection included demographic, psychometric, social network and physical activity data for the purpose of modeling the coevolution of health behaviors and social networks35. Participants’ sleep, heart rate and physical activity were monitored using Fitbit Charge HRs. Upon entering the study, participants were provided a Fitbit, along with a username and password to create their account with. This allowed the investigators to pull data directly from each account through Fitbit’s web API and store the data on a university server. To collect demographic and behavioral data, surveys were administered once per semester that students could complete online. To ensure completeness in the data collected, participants were asked to wear their Fitbit as much as possible and sync their device every 4−7 days.

### Ethics

This observational study was approved by the University of Notre Dame’s IRB after a full board review under protocol number 17-05-3912. All participants provided written informed consent prior to taking part in the study.

### Participants

Participants included 698 individuals who entered the university as first-year students over the course of the 2015–2016 academic year. The NetHealth cohort was split across three recruitment phases or “tiers” outlined below.

Tier 1: A total of 391 tier 1 participants were recruited via interest surveys, e-mail, and a Facebook page in June 2015. Selection was on a first come, first served basis in keeping with the overall demographic distributions of the university.

Tier 2: Next, 97 tier 2 participants were then recruited in November and December 2015, nominated by existing participants in the study.

Tier 3: Finally, 210 tier 3 participants were recruited via e-mail in April 2016.

Despite enrolling a total of 698 participants, not all were eligible for analysis. A total of 65 participants were excluded as they were not issued Fitbits (Fig. 3A), with reasons ranging from participants declining them to dropping the study before the device could be issued. Among the participants who received Fitbits, an additional 23 were excluded (Fig. 3B), as they did not wear their device while asleep. Finally, 11 participants were excluded as they did not report the demographic and behavioral data necessary for these analyses (Fig. 3C, D) and an additional 2207 sleep sessions were removed as physical activity data were missing for the previous day (Fig. 3E). At this stage, a cohort of 599 participants remained eligible for analysis.

#### Fig. 3. Flow diagram.

Outline of cohort selection and data pre-processing steps with the number of participants/data points removed at each step.

### Normal bedtime

To determine how deviations from one’s normal bedtime may affect RHR, a definition for “normal bedtime” was first necessary. To provide a standard measure across participants, with minimal influence from outliers, the median of a participant’s bedtimes was chosen to represent their normal bedtime. However, utilizing a single median bedtime to represent multiple years of sleep habits is likely insufficient. Participant’s may have adjusted their sleep schedules over time in response to changes in class schedules across semesters or in absence of class schedules during the winter and summer breaks. To adjust for these potential variations, participant’s median bedtimes were computed within each of these respective time periods, specifically, for each semester and winter/summer break.

### Deviations from normal bedtime

With normal bedtimes established, bedtime deviations were then measured by calculating the difference (in min) between a participant’s normal bedtime and recorded bedtime for each respective night. To avoid the assumption of a linear relationship between the degree of bedtime deviation and RHR, bedtime deviations were discretized: binned into 11 categories to be examined separately. The first category provided our baseline, which was nights when the participant went to bed reasonably close to their median bedtime. We allotted a range of 30 min earlier to 30 min later than one’s normal bedtime to be defined as an on time bedtime. The remaining ten categories focused on deviations from this baseline, occurring earlier or later. The intervals for these deviation categories were [1, 30) min, [30, 60) min, [1, 2) h, [2, 3) h, and ≥3 h.

### Naps

Among the 311,267 total sleep sessions, 66,552 records (21%) occurred on the same day, likely indicating days in which a nap was taken. Although naps are commonly raised in literature, a formal definition regarding their duration or timing throughout the day remains to be agreed upon36. Further, as Fitbit devices do not allow for the annotation of sleep periods, an unsupervised approach was taken to more rigorously identify and remove such noise.

This was accomplished by utilizing a Variational Bayesian estimation of a Gaussian Mixture Model (BGMM) for clustering each sleep session by their duration and bedtime deviation. Gaussian mixture models (GMM) have repeatably demonstrated success in modeling data generated by an arbitrary number of distinct Gaussian processes. Which, as we have seen in prior processing steps, can reasonably be expected to hold true for the approximately normal distributions of each student’s sleep records. Further, as variational inference adds a level of regularization beyond traditional GMM approaches, the BGMM is able to provide a more robust estimate of the true underlying sleep patterns needed to remove the ambiguous notion of naps from the data. Moreover, to avoid making assumptions about the underlying nature of the sleep clusters, the BGMM was fit with full covariance structures, allowing each identified component to vary in both direction and shape.

Finally, to evaluate the appropriate number of components (clusters) retrieved by the model, we defined a metric focused on rewarding the creation of distinct, nonoverlapping clusters in the data, a necessary addition, as Bayesian information criterion (BIC) is not applicable to BGMM. In an effort to identify stable, nonoverlapping clusters, we computed the average probability that each training point belonged to its respective cluster. To bound this, the average probability value is subtracted from 1, as the optimal situation would occur when every point is 100% likely to belong to its predicted cluster. Then, sweeping from 1 to 5 components, we selected the configuration that minimized this value, finding it to be 2 components (Fig. 4).

#### Fig. 4. Clustering of sleep sessions by duration and deviation from normal bedtime.

a The stability score as the number of components increases. b The distribution of sleep sessions for the optimal number of clusters, organized by sleep duration (y-axis) and deviation from normal bedtime (x-axis).

Among these two clusters, cluster 1 had a mean sleep duration of 7.03 h and mean bedtime difference of 1.04 h, while cluster 2 had a mean sleep duration of 2.26 h and mean bedtime difference of 6.7 h. Given the sleep sessions in cluster 2 had, on average, shorter durations and greater deviances from normal bedtimes, we removed sleep sessions within this cluster from our analysis as they more closely resembled characteristics of naps (Fig. 3f). In doing so, this also removed three participants, these participants likely only wore their device during naps, but removed the device before bed, failing to capture any full nights of sleep. Further, we removed the few remaining sleep sessions in which multiple sessions still occurred on the same day (Fig. 3g).

### Compliance

Finally, while NetHealth participants were followed for multiple years, not all participants were present for the full duration of the study. Reasons for this extended from participants entering the study late or having poor compliance to the study (not wearing their Fitbits) and abandonment of the study. To ensure participants with poor compliance would not bias the fixed effects of our models, we removed any participants with fewer than 30 sleep records, as having at least 30 units within each cluster is a commonly cited recommendation (Fig. 3H)37.

Following our compliance threshold, our data set consisted of 557 participants and 255,736 sleep sessions upon which we conducted our analyses. A distribution of the total sleep records contributed by participants is provided in Fig. 5, with the interquartile range for number of records contributed as follows: (Q1 = 161 records, Q2 = 379 records, Q3 = 736 records).

#### Fig. 5. Boxplot of total sleep records contributed by participants.

Boxplot statistics are as follows (Min = 31, Q1 = 161, Median = 379, Q3 = 736, Max = 1201).

### Resting heart rate

Our second research question focused on the amount of time for RHR to return to baseline, defined as the point in time when RHR following a bedtime deviation converged with RHR following no bedtime deviation. To ensure this return was fully captured, we examined, approximately, the 24-h period following one’s bedtime. Specifically, we monitored participant’s RHR beginning when they first went to bed until midnight of the following day. In doing so, it was necessary to examine RHR across periods when participants were asleep and awake. Given a variety of factors may influence RHR depending on when an individual is asleep or awake, we partitioned them into two separate analyses, taking two different approaches to best capture RHR for each state.

Sleep: Beginning with sleep, we assumed sleep stages: light sleep, REM and deep sleep, to be one of the primary factors influencing changes in RHR over one’s sleep session38,39. To minimize the potential for differences in RHR to be the result of comparing participants at different sleep stages, all sleep sessions were aligned by bedtimes. Next, sleep sessions were partitioned by hour (first hour of sleep, second hour of sleep, etc.), allowing each hour of sleep to be examined separately. RHR was then measured by computing the median RHR for each hour of sleep within each nightly record. Sleep sessions were truncated at 7 h to avoid missing data resulting from variations in lengths of sleep sessions. Seven hours was chosen specifically, as this was the median sleep duration across participants. Finally, we note that in examining RHR across sleep, 14,877 sessions were missing RHR data, likely stemming from device failure rather than failure to wear the device, as bedtimes and sleep durations were still recorded (detected by the Fitbit accelerometer). As such, these sessions were excluded (Fig. 3I).

Awake: As factors influencing RHR throughout one’s sleep are primarily relative to when one begins sleeping, the same does not hold for when one is awake. Specifically, factors influencing one’s RHR throughout the day are not necessarily relative to when one wakes up. Instead, individuals tend to keep with a daily social rhythm, where events correspond more to time of day, than when one wakes up40,41. For example, because one wakes up an hour later than usual, this does not necessarily mean they will also have lunch 1 h later than usual, as lunch time is determined more by time of day. Additional facets of these social rhythms can include adherence to a class schedule, leaving and returning from work, etc. which can affect RHR40,41. Therefore, when measuring RHR over the following day, we instead computed the median RHR for each hour of the day (9:00 am to 9:59 am, 10:00 am to 10:59 am, etc.) to better compare RHR across these social rhythms. Further, to capture RHR instead of HR, we only considered periods in which the participant had been inactive (no steps) for at least 30 min, in line with prior literature, with measurements ending when the participant began moving again42–44. Lastly, we note that in examining RHR across the following day, 51,368 days were excluded due to missing data as participants likely failed to wear their device throughout that day (Fig. 3J).

### Previous days’ physical activity

As detailed in the next section of the manuscript, we adjusted for several additional variables associated with RHR. Among these was the amount of physical activity the participant engaged in the day before, as physical activity has been shown to have an association with sleeping heart rate45. Fortunately, Fitbits also capture levels of physical activity based on heart rate readings. Fitbit partitions a user’s physical activity into three different heart rate zones based on the intensity of their activity: Fat Burn, Cardio, and Peak46. Therefore, we represent physical activity as the total amount of minutes a participant spent in any of these zones for each day. While a participant would predominantly spend their time in the Fat Burn range, as this can be accomplished through walking, this zone was included to adjust for the association of even light levels of physical activity, as any even light physical activity will increase heart rate.

Overall, our cohort eligibility requirements and preprocessing steps left us with two overlapping data pools: a total of 240,859 sleep sessions for assessing RHR over sleep and a total of 204,368 days for assessing RHR when awake over the following day.

### Modeling

To evaluate the association between bedtime deviations and RHR, we fit a series of linear mixed effects models, one for each hour of sleep and one for each hour of the following day up until midnight. This approach allowed us to assess both of our research questions simultaneously. For each hour following a deviation, we could examine whether differences in RHR were present (RQ1) and how long they persisted for (RQ2). Further, examining each hour independently allowed us to capture nonlinear trends in RHR over time. To supplement the models capturing these hourly level changes, we fit two additional mixed effects models for mean RHR: one over participants entire sleep session and the other over the following day; these models provided us a broad overview of the associations.

The decision to employ linear mixed effects models allowed us to account for the inter-instance correlation of sleep session data recorded multiple times for each individual. Further, they accounted for an additional source of variance. Specifically, the latent relationship between the time of day and an individual’s RHR moderated by their circadian rhythm.

A naturally occurring biological pattern, the circadian rhythm, dictates changes in the behavior and/or physiology of most species and has been shown to account for hourly variations in HR38,41,47,48. Unfortunately, rather than simply a global shift based on the absolute time of day, each individual can be expected to experience slightly differing effects at different times of day based on a broader consideration of their chronobiology49. As such, we extend the repeated measure mixed effects model to a multilevel model in which we nest observations for each absolute time of day under each individual. By accounting for variability in RHR by each hour of the day for a specific individual, we reduce the likelihood of finding a difference in two RHR measures because they were simply measured at different points of an individual’s circadian rhythm. Following this, we nest observations within individuals to account for the variability in RHRs between individuals. Ultimately, this approach provides a significantly more robust estimation of the unbiased effects of each covariate on the RHR based on deviations in bedtimes.

### Covariates

In addition to circadian rhythm, we also adjusted for several confounding variables, including features of one’s sleep session and external influences on RHR. External influences, such as sex and caffeine and alcohol consumption, were collected via the biannual surveys administered to participants. In the case of participants missing a survey, fill-forward/backward imputation was utilized, allowing these imputed values to most closely reflect participants true scores at the time and satisfy model requirements. We detail each of these variables below.

Sleep duration—as prior work has associated insufficient sleep with increases in RHR, sleep duration was included in the model50.

Naps—as some individuals may regularly account for sleep debt with naps in between nightly sessions, we include a binary flag for whether an individual had taken a nap over the previous day to adjust for this alternative sleep schedule.

Sex—prior works have found differences in RHR between sexes with women having, on average, a higher RHR of 3–7 bpm32.

Caffeine and alcohol consumption—we further adjusted for participants frequency of caffeine and alcohol consumption as both compounds have been found to be associated with increases in heart rate32,33.

Prior day physical activity–as prior studies have found an association between physical activity and sleeping heart rate, the amount of physical activity engaged in the previous day was included in the model45.

The last covariate considered for the model was day of the week, as weekend nights may be more likely to bring about behaviors associated with increased sleeping heart rate, such as alcohol consumption. However, bedtime deviations and weekends are likely to be highly correlated given the natural tendency to stay up later on weekends, resulting in stronger bedtime deviations on the weekends. We find this assumption holds true among this cohort, as performing a chi-square test of independence on the frequencies of bedtime deviations stratified by weekday and weekend shows the difference between the distributions to be statistically significant (P < 0.001), with individuals going to bed later more frequently on the weekends.

To ensure increases in RHR were not solely a product of weekend behavior, we reconducted our analysis, this time using only weeknights (Sunday–Thursday). From our results, we observed similar changes in RHR using only weeknights suggesting the increases in RHR following a bedtime deviation are independent of weekend behaviors. Details for this analysis are provided in the supplementary materials: Supplementary Methods 2.

### Reporting summary

Further information on research design is available in the Nature Research Reporting Summary linked to this article.

## Written summary (not copied text)

*Written 2026-10-19 from the text saved in this file only, following derived/study-summary-template.md; nothing looked up online. Where the saved text does not give a detail, the summary says so.*

### A Later Bedtime Raises Heart Rate Into the Next Day

In a 2020 study, researchers at the University of Notre Dame in the USA analysed over 255,000 nights of Fitbit data from 557 college students followed for up to four years.

Going to bed even 30 minutes later than usual was linked to a slightly higher resting heart rate through the night, lasting into the next day until early evening. Going to bed an hour or more earlier than usual also raised heart rate during sleep, but it was back to normal by morning.

**The main takeaway:** Irregular bedtimes, especially later ones, nudge up your resting heart rate, a sign that sleep timing matters as well as sleep length.

**Quick facts**

- **Authors:** Faust L, Feldman K, Mattingly SM, Hachen D, Chawla NV
- **Link:** https://pmc.ncbi.nlm.nih.gov/articles/PMC7090013/
- **Published in:** *npj Digital Medicine* (peer-reviewed journal)
- **Study type:** Observational cohort (wearable data)
- **Age range:** College students (exact range not stated in the saved text)
- **Measures:** Fitbit Charge HR bedtimes, sleep and resting heart rate
- **Caveat:** Observational; the effect per night is small (about 0.18 beats per minute for 30 minutes late); students only
- **Replication:** Not checked (saved text only)
- **Evidence:** Moderate (very large dataset, but association only and small effect)
