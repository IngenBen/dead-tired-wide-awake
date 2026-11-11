# Continuation prompt — blind-endnotes sourcing for the MED claims

*(Paste everything below into a new chat in this project. It is self-contained.)*

---

ROLE & CONTEXT
You are the maintainer of the "Sleep Incorporated" book vault. **Read `CLAUDE.md` in the project
root first and follow it exactly.** Key rule: `/book/` is the finished manuscript and is
**read-only** — you read it for claim context only; every proposed change is written to `/audit/`,
never to `/book/`.

We have just finished sourcing references for all **61 HIGH** claims. That deliverable is
`/audit/claim-references.md` (with working notes in `/audit/claim-references-working.md`). **Read
both before you start** — reuse their format exactly, and reuse sources already retrieved there
(many MED claims will share a fact/source with a HIGH claim already done).

TASK
Do the same blind-endnotes sourcing for the **142 MED** claims in `scratch-pad-claims-ranking.md`
(root). MED = a general scientific/mechanistic claim (broadly accepted, worth a further-reading
pointer), OR a contested/counterintuitive claim a reader might not expect. So "supports at T2/T3"
is usually enough; spend your scrutiny on the contested/counterintuitive ones and any numbers.

GOAL
For each MED claim, find the single best available reference using the hierarchy below. Work
top-down; STOP at the first tier where you find a real, verified, qualifying source; record that
tier; move on. **Never fabricate or guess.**

WORK IN STEPS, AND PAUSE FOR INPUT BETWEEN EACH (this is important — do not run ahead):

- **STEP A — Tally first, then PAUSE.** Open `scratch-pad-claims-ranking.md`, count the MED claims,
  give a per-chapter breakdown and confirm the total (should be 142). Note which chapters carry the
  most. Then stop and wait for go-ahead.
- **STEP B — Expand & cluster, then PAUSE.** For each MED claim, open the cited chapter in `/book/`
  and write (i) the full claim as one sentence and (ii) the exact source sentence(s). Group claims
  that assert the same fact (de-dupe; pick one canonical claim per group and source once). Split any
  stub that bundles two facts. Group the distinct facts into topic clusters (caffeine, melatonin,
  cortisol, etc.). Write this scaffold to `/audit/claim-references-MED-working.md`. Report: number of
  distinct facts and number of clusters. Then stop and wait.
- **STEP C — T1/T2 authoritative-body sweep, then PAUSE.** Search each distinct fact for Tier 1/2
  support (authoritative bodies). Record verbatim quotes + number checks. Report counts: resolved /
  concept-confirmed-but-number-pending / not-found-at-T1-T2. Then stop and wait.
- **STEP D — Deeper tiers (T3–T6) for the remainder.** Do this in batches of ~5–6 clusters, balanced
  by fact-count, **pausing between passes**. Flag contradicts / mixed / no-source as you go.
- **STEP E — Compile `/audit/claim-references-MED.md`** in the same per-claim format as the HIGH file,
  plus a tier tally and a list of every claim flagged contradicts/mixed/no-source/number-off. Append
  a `log.md` entry.

REFERENCE HIERARCHY (best → weakest; stop at first verified, qualifying hit)
- **T1** Authoritative body WITH data — guideline/position statement/data report from a top body
  (WHO, NIH/NHLBI/NINDS/NIA, CDC/NIOSH, NHS, NICE, AASM, Cochrane, EFSA, Sleep Health Foundation AU,
  National Sleep Foundation, Menopause Society/NAMS/IMS, or equivalent) that presents/cites
  quantitative data.
- **T2** Authoritative body, states the claim as established, no specific numbers.
- **T3** Strong primary literature — systematic review/meta-analysis, or multiple consistent
  peer-reviewed studies, with few/no credible disconfirming studies.
- **T4** Supported by extension — studies support a closely related claim; the book's claim is a
  reasonable generalisation. Allowed ONLY here, and you MUST state the inferential gap.
- **T5** Mixed evidence — credible studies on both sides; cite both.
- **T6** Non-academic — specific book, named podcast episode, reputable web source. Flag as weak.
- **NONE** After a genuine good-faith search, no source found. Say so. Never invent one.
Prefer the most recent authoritative source. A current guideline/Cochrane review outranks an old
single study.

HARD RULES (anti-fabrication)
- Cite only a source you actually retrieved and read **this session**.
- Every citation = a working DOI/URL you opened **plus** a verbatim 1–2 sentence quote that supports
  the claim.
- If the claim has a number/dose/threshold, confirm the source states the same figure. If it differs,
  record the discrepancy — do not round to fit.
- No inference beyond T4, and label it when used. "No source found" is an acceptable answer.

OUTPUT FORMAT (per claim — copy the HIGH file's structure)
Claim ID + canonical group · Expanded claim · Book source sentence · Tier · Citation (author/org,
year, title, journal/publisher, DOI/URL) · Verbatim quote · Number/dose check (Y/N/NA + note) ·
Evidence status (supports/partial/mixed/contradicts) · Author flag (e.g. "number differs", "weak
source only", "evidence contradicts — consider softening", or none) · Searches run.
End with: a tally by tier, and a short list of every claim flagged contradicts/mixed/no-source.

──────────────────────────────────────────────────────────────────────────
CRITICAL OPERATIONAL LESSONS (carry these forward — they cost real time to learn)

1. **Read `/book/` with the file-reader (Read tool), NOT the bash shell.** This vault is OneDrive
   files-on-demand; the shell can silently hand back **truncated chapter tails**. (In the HIGH pass,
   bash `cat` cut the ends of ch07/18/24.) Use Read for every chapter.

2. **PMC (pmc.ncbi.nlm.nih.gov) is CAPTCHA-blocked — do not fetch it.** Instead use the **Europe PMC
   REST API**, which returns the abstract as JSON and is reliable:
   - by PMID:  `https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=EXT_ID:<PMID>&resultType=core&format=json`
   - by PMCID: `https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=PMCID:PMC<id>&resultType=core&format=json`
   - by DOI:   `https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:"<doi>"&resultType=core&format=json`
   The `abstractText` field is your verbatim quote source.

3. **Never guess a PMID.** Several guessed PMIDs returned the *wrong* paper (e.g. a ghrelin paper,
   a teacher-efficacy paper). Always get the exact PMID/PMCID/DOI from a WebSearch result first,
   then fetch by that ID, and **verify the returned title matches** what you expect.

4. **`web_fetch` is rate-limited (HTTP 429).** Pace it: 1–2 fetches at a time; use WebSearch (separate
   limit) to pin IDs; do file Edits between fetches to let the limit cool. Europe PMC keyword
   searches are noisy — prefer exact EXT_ID/PMCID/DOI lookups.

5. **PDFs don't parse via `web_fetch`** (publisher/repository PDFs come back empty). Use the indexed
   abstract; if a specific figure lives only in the body, note it as "full-text check needed" rather
   than guessing.

6. **WebSearch is US-only** — deliberately also check AU/UK/international bodies. For this Australian
   book, the **Sleep Health Foundation (AU)** fact sheets and AU research groups (Monash Turner
   Institute, Flinders, ACU) are gold and on-voice.

7. **Reuse the HIGH pass.** Sources already retrieved that recur for MED claims: NINDS *Brain Basics:
   Understanding Sleep* (sleep stages, adenosine, REM, circadian, melatonin/light), SHF fact sheets
   (caffeine / alcohol / melatonin), CDC & CDC-NIOSH, AASM CBT-i guideline, Reichert 2022 (adenosine),
   Russo 2017 (slow breathing/vagus), Okamoto-Mizuno 2012 (temperature), Gardiner 2024 (alcohol),
   Spiegel 2004 (ghrelin/leptin), de Nys 2022 (exercise/cortisol). De-dupe MED claims against facts
   already sourced in `claim-references.md` before re-searching.

8. **Use the task list and AskUserQuestion** as in the HIGH pass; checkpoint at every PAUSE above.

START WITH STEP A (the tally) and then stop for input.
──────────────────────────────────────────────────────────────────────────
