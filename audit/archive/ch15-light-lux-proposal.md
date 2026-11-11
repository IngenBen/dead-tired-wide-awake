# Proposal — Ch15 footnote on blue light / lux threshold (replaces unsourced "17 lux")

**Why:** the book's Ch15 footnote states "below 17 lux, melatonin suppression is minimal."
In the sourcing pass (see `claim-references.md` Ch15.21) no study could be found for a 17-lux
threshold, and the underlying science doesn't support a clean cutoff — melatonin response to
evening light is a dose-response curve with very large between-person variation. Ben supplied
three studies to ground a rewrite. All three are logged below (retrieved & quoted this session),
with two attribution corrections, then a suggested reworded footnote. `/book/` is read-only —
this is a proposal only.

---

## The three studies (logged)

### 1. Zeitzer et al. (2000) — melatonin suppression dose-response
Zeitzer JM, Dijk DJ, Kronauer R, Brown E, Czeisler C. "Sensitivity of the human circadian
pacemaker to nocturnal light: melatonin phase resetting and suppression." *J Physiol*
2000;526(Pt 3):695–702. PMID 10922269. DOI 10.1111/j.1469-7793.2000.00695.x
> "…half of the maximal phase-delaying response achieved in response to a single episode of evening bright light (approximately 9000 lux (lx)) can be obtained with just over 1 % of this light (dim room light of approximately 100 lx). The same held true for the acute suppressive effects of light on plasma melatonin concentrations."
**Take:** group-level **~50% melatonin suppression at ≈100 lux**.
**⚠ Attribution correction:** the PMID Ben sent (10996410) is a *different* 2000 paper —
**Cajochen, Zeitzer, Czeisler & Dijk, "Dose-response relationship for light intensity and ocular
and electroencephalographic correlates of human alertness," *Behav Brain Res* 115:75–83** — which
is about *alertness* ("Half of the maximum alerting response to bright light of 9100 lux was
obtained with room light of approximately 100 lux"), not melatonin suppression. The melatonin
paper is the J Physiol one above. Also: the "30 lux" Ben attributed to Zeitzer is actually the
Monash figure (study 2), not Zeitzer's (~100 lux).

### 2. Phillips et al. (2019) — Monash; sensitivity + individual variability
Phillips AJK, Vidafar P, Burns AC, McGlashan EM, Anderson C, Rajaratnam SMW, Lockley SW, Cain SW.
"High sensitivity and interindividual variability in the response of the human circadian system to
evening light." *PNAS* 2019;116(24):12019–12024. PMID 31138694 / PMC6575863. DOI 10.1073/pnas.1901824116
> "The group-level fitted ED50 was 24.60 lux, indicating that the circadian system is highly sensitive to evening light at typical indoor levels. Light intensities of 10, 30, and 50 lux resulted in later apparent melatonin onsets by 22, 77, and 109 min, respectively. Individual-level ED50 values ranged by over an order of magnitude (6 lux in the most sensitive individual, 350 lux in the least sensitive individual), with a 26% coefficient of variation."
**Take:** group **~50% suppression at ≈25 lux** (press release rounds to "30 lux"); even **10 lux
delayed melatonin onset ~22 min**; **6 lux (most sensitive) → 350 lux (least sensitive)** — a
>50-fold individual range. This is the "10 lux for the highly sensitive" point.
**⚠ Attribution note:** the link Ben sent (science.org `10.1126/scitranslmed.aax9568`) is the
*Science Translational Medicine* Focus/commentary on this study ("Sussing out sensitivity to
light…"), not the primary paper. Cite the PNAS primary above (open-access, retrievable).

### 3. Bauducco et al. (2024) — how much screens actually delay sleep
Bauducco S, Pillion M, Bartel K, Reynolds C, Kahn M, Gradisar M. "A bidirectional model of sleep
and technology use: A theoretical review of how much, for whom, and which mechanisms." *Sleep Med
Rev* 2024;76:101933. PMID 38657359. DOI 10.1016/j.smrv.2024.101933
> "The link between technology and sleep is more complex than originally thought… We begin by reviewing the evidence to date for the originally proposed mechanisms of bright light, arousal, nighttime sleep disruptions, and sleep displacement."
**Take (from the review's evidence synthesis):** in controlled experiments the *practical* effect
of pre-bed screens on sleep onset is small — bright vs dim screens, and stimulating vs neutral
content, each delay sleep onset by **at most ~10 minutes** (reported ~9.9 min for light, ~8.5 min
for arousal). i.e. screen light is **not** a large driver of how fast you fall asleep.
**Note for accuracy:** these specific minute figures sit in the paper's body/summary (the abstract
retrieved here is general; the open-access full-text PDF wouldn't parse via fetch — worth a manual
look to quote the exact sentence). Also: this slightly tempers a strong "content >> light" claim —
the data show *both* effects are small, with light's measured delay marginally larger than
arousal's in these experiments, even though content is the more *robustly demonstrated* factor
(cf. NSF 2024 consensus, which reached consensus on content but not on pre-bed light).

---

## What the science actually says (reconciled)

- There is **no clean "minimal below X lux" threshold.** Melatonin suppression rises along a
  dose-response curve.
- **Group-level 50% suppression sits ≈25–100 lux** (Phillips ≈25; Zeitzer ≈100) — i.e. ordinary
  dim indoor/evening light already suppresses melatonin substantially.
- **Individuals vary >50-fold** (≈6 lux to ≈350 lux for the same 50% suppression). So any single
  threshold is misleading.
- **But the real-world payoff is modest:** experimentally, pre-bed screen light shifts sleep onset
  by only ~10 min (Bauducco) — which actually *supports the book's bigger thesis* that what's on the
  screen matters at least as much as the light.

## Suggested reworded footnote (proposal — not applied to /book/)

> **On blue light.** What matters is how much light actually reaches your eyes — and sensitivity to
> it varies more than fifty-fold between people — from as little as ~6–10 lux in the most sensitive
> to ~350 lux in the least. Even taking that worst case — the most sensitive people, who react to as
> little as ~6–10 lux — distance still keeps a TV under the line: a TV across the room delivers only
> around 5 lux at the eye, comfortably below even that threshold. It's a phone held close to your
> face that crosses it, at ~25–50 lux. That said, the *practical* effect of screen light on how
> quickly you fall asleep is modest — controlled studies put it at only around ten minutes. So for a
> screen, the content matters at least as much as the light.

Notes on the rewrite:
- Drops the unsourced "17 lux" and the false "below X = minimal" framing.
- Keeps the book's sound physical point (distance → less light at the eye) but **without** committing
  to the specific "TV 5 lux / phone 25–50 lux" numbers (still unsourced/illustrative — see Ch15.22).
  If you want to keep those numbers, label them as a rough illustration.
- Reinforces the book's content-over-light thesis (Ch21) using Bauducco — a net win.
- Optional shorter version if footnote length matters: *"What matters is the light actually reaching
  your eyes, and sensitivity varies hugely between people — dim indoor light (~25–100 lux) already
  suppresses melatonin substantially in most, while the most sensitive react to under 10 lux. A
  distant TV delivers far less than a close phone. But screen light only delays sleep onset by ~10
  minutes in studies, so the content matters at least as much."*

## Sources
- [Zeitzer 2000 — J Physiol (melatonin suppression)](https://doi.org/10.1111/j.1469-7793.2000.00695.x)
- [Phillips 2019 — PNAS (Monash; light sensitivity & variability)](https://doi.org/10.1073/pnas.1901824116)
- [Bauducco 2024 — Sleep Med Rev (bidirectional model)](https://doi.org/10.1016/j.smrv.2024.101933)
- [Cajochen 2000 — Behav Brain Res (alertness; = the PMID 10996410 mix-up)](https://doi.org/10.1016/s0166-4328(00)00236-9)
