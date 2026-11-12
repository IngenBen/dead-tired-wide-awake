# Operation Log

Append-only. One entry per operation.

---

## [2026-06-30] audit | phase structure + three-pillars proposals → /audit/phase-structure-three-pillars.md
Three related proposals: (1) Social media moves from Phase 5 to Phase 6 ("optimise your inputs" extended to cover mental inputs alongside physical); (2) new Phase 6 intro text framing the phase as the subtler disruptors, sequenced last because earlier phases needed to work first; (3) ch22 opening sentence explicitly naming social media as mental input parallel to the physical inputs around it. Exercise move to Phase 4 noted as raised but undecided.

## [2026-06-30] derived | three-pillars habit mapping → /derived/three-pillars-mapping.md
Mapped all 12 habit chapters (ch14–ch25) to the marketing frame "train your body clock / build your nervous system / remove disrupters." Assignments reflect author reasoning supplied in session: caffeine = disrupter (architecture + clock); alcohol = disrupter (architecture); can't sleep = build NS (breaking night activation pattern); morning + evening = body clock only (evening's NS handoff line is a transition, not an assignment); meditation = build NS; napping = build NS + remove (body clock / adenosine); exercise = build NS (yoga builds calm; intensity timing reduces activation); social media = remove (NS disrupter + clock disrupter); hydration = remove; food timing = remove; sugar = remove (sleep + NS). File includes author-supplied reasoning, supporting snippets, and summary grid.

## [2026-06-26] audit | KB alignment pass — claims-knowledge-base.md updated to match endnotes-final.md
Updated all 13 affected KB entries to match the rewritten endnotes: 8 heading changes + body text rewrites for all 13. Corrective/contradicting framing replaced with explanatory/supportive framing throughout. Entries updated: Ch05 adenosine (near zero → largely lifted), Ch05 alcohol (suppress slow-wave → absent from disruptors list), Ch06 melatonin peak (midnight-or-one estimate → middle of night explanation), Ch07 cortisol pre-waking (conflation note → CAR as distinct post-waking surge), Ch12 temperature biology (most direct → wired into biology mechanism), Ch12 temperature drop (Celsius double note → peripheral vasodilation mechanism), Ch13 half-life (six-hour overstates → roughly five hours is reasonable), Ch14 alcohol deep sleep (fragment/uncleared → sedative artefact and REM displacement), Ch14 zero alcohol (not flat zero → book presents both health-guidance and sleep-specific framings), Ch14 drink cost 1-2 (specific minutes removed → measurable, dose-dependent direction), Ch14 drink cost 3-4 (specific minutes removed → more drinks = more disruption), Ch15 lux (17 lux unsupported → ED50 and individual range explanation), Ch16 movement (amplifies → complementary zeitgeber), Ch20 exercise (morning + baseline qualifiers removed → regular exercise supports healthier cortisol and sleep).

## [2026-06-26] audit | endnotes alignment pass — endnotes-final.md updated
Read all 20 chapters with endnotes against the 47 notes in endnotes-final.md. Found 9 clear mismatches (endnote arguing against a claim the book no longer makes, due to applied proposed edits) and 4 framing issues (endnote's corrective angle not matching the current book wording). Applied 13 rewrites: 6 heading changes + body rewrites for all 13. Notes converted from corrective to explanatory/expansive where the book's claim had been softened (Ch05 "largely lifted", Ch06 "middle of the night", Ch12 temperature figures, Ch13 five-hour half-life, Ch14 alcohol deep sleep, Ch15 lux figures). One new source added to Ch14 "How much restorative sleep" note (Ebrahim IO et al. 2013). Ch05 alcohol note repurposed to explain why alcohol was deliberately omitted from that chapter's disruptors list.

## [2026-06-25] derived | MED claims (135) merged into unified KB -> /derived/claims-knowledge-base.md
135 MED claims interleaved with existing 61 HIGH entries to produce one unified knowledge base (156 entries total, Chapters 1–24). Entry count is 156 distinct headings because many MED claims are cross-references that point to existing HIGH entries rather than spawning fully duplicate entries. New chapter groups added for Ch01, Ch02, Ch08, Ch09, Ch19 (chapters with MED claims but no prior HIGH entries). Cross-references used for MED claims that restate an existing HIGH entry (rather than duplicating sources). Contested marker <!-- contested --> applied to all T4/T5-tier and [FIX]/[SOFTEN]/[NUMBER]-flagged MED claims. Source links drawn from claim-references-MED-sources.md via group codes; two SOURCE TO FIRM placeholders carried forward (Ch12.10 temperature range; Ch15.22 lux values). All original HIGH headings preserved verbatim. /book/ untouched.

## [2026-06-25] derived | HIGH claims (61) substantiated -> /derived/claims-knowledge-base.md
All 61 HIGH claim IDs assembled into standardised knowledge-base entries (neutral register, no invented sources, contested claims marked <!-- contested -->). Grouped by chapter (Ch03–Ch24), in claim-ID order. Cross-references used for canonical-merged pairs (Ch13.10/Ch24.5 self-control; Ch05.12/Ch14.8 alcohol). Two entries left with SOURCE TO FIRM placeholders: Ch12.10 (16–26°C temperature range, no primary source identified) and Ch15.22 (TV ~5 lux / phone 25–50 lux, illustrative values not pinned). Misattributions and internal inconsistencies flagged in return message. /book/ untouched.

## [2026-06-24] schema | endnote presentation style locked -> CLAUDE.md
Author decision: no in-text markers (no superscripts, no ⟦EN:…⟧ in prose). Back-matter Notes grouped by chapter, notes in reading order, each headed by a ~5-8 word identifying question, then author-voice summary + source(s) (no "Sources:" label, caveats as parentheticals). Compilable now without applying proposals to /book/ (order is positional within chapter, not a global running number). Working file endnotes-draft.md keeps claim IDs/decision types/attach points; clean reader-facing version to be compiled to /audit/endnotes-final.md. Added as new "ENDNOTE PRESENTATION STYLE" subsection in CLAUDE.md. Supersedes the earlier numbered-back-matter plan.

## [2026-06-24] endnote | citation-format normalization -> /audit/endnotes-draft.md
Step 2 of endnotes work. Replaced all bare aggregator/marketing URLs with publisher DOIs/stable links and added missing author/year/vol where absent (verified via WebSearch; web_fetch rate-limited all session):
- Ch08.6/10/12 + Ch08.14 "Engineered highs" (was ScienceDirect pii) → Clark L, Zack M 2023, Addict Behav 140:107626, DOI 10.1016/j.addbeh.2023.107626.
- Ch08.14 Berridge (was ResearchGate) → corrected MISATTRIBUTION: single-author Berridge KC 2007 (draft said "Berridge & Robinson"), Psychopharmacology 191:391-431, DOI 10.1007/s00213-006-0578-x.
- Ch10.16 Shaffer & Ginsberg → frontiersin URL swapped for DOI 10.3389/fpubh.2017.00258.
- Ch10.21 Oura: PubMed link → Svensson T, Madhawa K, et al. 2024, Sleep Medicine 115:251-263, DOI 10.1016/j.sleep.2024.01.020; Oura marketing-blog link → Robbins R, Weaver MD, et al. 2024, Sensors 24(20):6532, DOI 10.3390/s24206532.
- Ch11.11 magnesium: Amazon + Magtein.com blog removed → Liu G et al. 2016, J Alzheimers Dis 49(4):971-990, DOI 10.3233/JAD-150538 (research dosing/split); the 144 mg/2 g elemental figure reframed honestly as label-derived/arithmetic (no peer-reviewed source exists — not invented).
- Ch13.6 EFSA 2015 → added DOI 10.2903/j.efsa.2015.4102.
- Ch24.20 Calder (was bare PMC link) → corrected MISATTRIBUTION: lead author is Minihane A-M et al. (Calder PC senior), Br J Nutr 114(7):999-1012, DOI 10.1017/S0007114515002093.
- Style: author-year→journal separator normalised to comma (Gerdin, Menczel, George, Andersson).
Left as-is (already stable, not aggregators): SCIRP publisher page (Ch18.32), Europe PMC link (Ch24.11 Sweatt), Ch03.1 DOIs (lack vol:pages but DOI carries it). /book/ untouched.

## [2026-06-24] endnote | Ch23.13a optional primary added -> /audit/endnotes-draft.md
Added one primary source under the Sleep Foundation/Northwestern consumer cites, verified via Europe PMC core record (user-pasted): Riley TM, Kris-Etherton PM, Hart TL, Petersen KS 2024, J Nutr 154(4):1219-1231, DOI 10.1016/j.tjnut.2024.01.021 (PMID 38278217, OA), 12-wk randomized crossover in prediabetes — protein/fat nighttime snack ≈ carbohydrate snack on glycemic markers (null). Supports the "type isn't a settled winner" position; noted the American Pistachio Growers part-funding (finding is a null). No prose change; /book/ untouched.

## [2026-06-24] endnote | Ch24.21 brain-fog study named -> /audit/endnotes-draft.md
Named PMC11857395 via Europe PMC core record (user-pasted): Altinsoy C, Dikmen D 2025, Medicina (Kaunas) 61(2):344, DOI 10.3390/medicina61020344 (PMID 40005460, OA), "How Are Brain Fog Symptoms Related to Diet, Sleep, Mood and Gastrointestinal Health? A Cross-Sectional Study." Also corrected the journal (draft had it as Nutrients; actually Medicina) and noted the long-COVID context. NHS cite unchanged. Bare PMC link swapped for DOI. No prose change; /book/ untouched.

## [2026-06-24] endnote | Ch24.20 attribution corrected -> /audit/endnotes-draft.md
Verified PMC8625578 via Europe PMC core record (user-pasted): the "Zopf Y et al. 2021, Nutrients" attribution was WRONG on both author and journal. Actual article = Myszkowska D, Zapała B, Bulanda M, Czarnobilska E 2021, Medicina (Kaunas) 57(11):1245, DOI 10.3390/medicina57111245 (PMID 34833463, OA), "Non-IgE Mediated Hypersensitivity to Food Products or Food Intolerance—Problems of Appropriate Diagnostics." Content matches the endnote point (non-IgE reactions real; IgG4/cytotoxic tests not clinically relevant). Corrected attribution and swapped bare PMC link for DOI. No prose change; /book/ untouched.

## [2026-06-24] endnote | Ch24.11-16-17 chain citations firmed -> /audit/endnotes-draft.md
Pinned both soft bullets via Europe PMC core records (user-pasted). (1) Counter-regulation review now named: Verberne AJ, Sabetghadam A, Korim WS 2014, Front Neurosci 8:38, DOI 10.3389/fnins.2014.00038 (PMID 24616659, OA) — abstract confirms declining glucose triggers glucagon/adrenaline/cortisol/GH, supporting the "low → cortisol" step; replaces the vague "see Ch24.12/13 notes" pointer. (2) Nutrients 2026 study named: Sweatt SK, Thomas DM, LaPorte GJ, Chauff S, Stefanovski D, Gower BA 2026, "Defining and Characterizing Postprandial Reactive Hypoglycemia," Nutrients 18(5); bare PMC link swapped for europepmc.org/article/PMC/PMC12986748. No prose change; /book/ untouched.

## [2026-06-24] endnote | Ch22.7-8 citation firmed -> /audit/endnotes-draft.md
Replaced the bare "background physiology" line with two pinned, verifiable sources for the well-grounded half (overnight vasopressin → reduced nocturnal urine; sleep depth/arousal governs awareness): George CP et al. 1975 (J Clin Endocrinol Metab 41:332-338, DOI 10.1210/jcem-41-2-332 — classic primary, nocturnal AVP rise) and Andersson KE & Van Kerrebroeck P 2018 (Curr Urol Rep 19:8, DOI 10.1007/s11934-018-0750-y — nocturia/NP review). Cortisol→bladder step kept explicitly flagged as the author's inference. Verbatim/biblio confirmed via WebSearch (Europe PMC web_fetch rate-limited this session). No prose change; /book/ untouched.

## [2026-06-22] claim-action | alcohol cluster (ch05 + ch14) -> /audit/ch05-proposed.md, ch14-proposed.md
Coordinated rewrite, all decided EDIT. Driven by two assets: why-we-wake-at-2-3am.md (§7: adenosine decline is gradual, not "near zero"; SWA front-loading is the robust part) and what-alcohol-does-to-your-sleep.md (§6–8: alcohol increases early SWS, does not block adenosine clearance; cost is continuity/REM/autonomic).
- Ch05.12 EDIT — alcohol bullet removed from the deep-sleep-disruptor list (miscategorised; covered in Ch14).
- Ch05.5 EDIT — "near zero by morning" softened to "that pressure has largely lifted"; single-lever "comes down to one thing" lightly hedged (marked optional/revertable). Reverses the action-list "accept" after the asset review.
- Ch14.2 EDIT — "zero alcohol is the recommended position" reframed: zero = overall-health (WHO 2023), sleep = less/timing.
- Ch14.8 EDIT — "fragments deep sleep" removed; REM suppression kept; deep sleep noted as preserved/front-loaded.
- Ch14.9 / 14.10 EDIT — unverified 15-/40-min figures removed, softened to qualitative dose-response (full-text chase offered, not done).
- Ch14.11 EDIT — adenosine-clearance hangover mechanism replaced with continuity/REM/autonomic non-recovery.
Full chapters recreated as proposals (per author request) rather than per-claim edit files. /book/ untouched.

## [2026-06-22] claim-action | ch07 -> /audit/ch07-proposed.md
- Ch07.7 EDIT (must-fix) — "cortisol awakening response" mislabel resolved by dropping the term entirely (author's call: adds no weight, never recurs). Pre-waking circadian rise + "peaks in the first hour or so after waking" retained (already accurate per Fries 2009). Full chapter recreated as a proposal (matches ch05/ch14 pattern). /book/ untouched.

## [2026-06-22] claim-action | ch15 -> /audit/ch15-proposed.md
- Ch15.21 EDIT (must-fix) — "below 17 lux, melatonin suppression is minimal" removed (no source; biology is a dose-response curve, not a threshold). Footnote reworded to: sensitivity differs, typical ~25 lux (Phillips 2019, ED50 24.6), most sensitive 6–10 lux → even most sensitive unlikely affected by a ~5-lux TV.
- Ch15.22 EDIT — TV ~5 lux / phone-tablet 25–50 lux figures KEPT (author's call), reframed structurally; remain illustrative of the distance principle, not measured. Footnote may break voice (author approved).
- New support folded into footnote: ~10-min screen-light onset delay (Bauducco 2024) + NSF expert-panel consensus, content disrupts sleep / light not agreed (Hartstein 2024).
- Endnotes tracking: Hartstein 2024 already on sources list under Ch21.3; cross-referenced to Ch15 in claim-references-sources.md so the endnotes pass attaches it here too. Folded in the existing ch15-light-lux-proposal.md. /book/ untouched.

## [2026-06-22] claim-action | ch06 -> /audit/ch06-proposed.md
- Ch06.9 EDIT — "won't peak until around midnight or one" → "It peaks and holds high through the middle of the night." Drops the early/unsourced figure; aligns with assets/why-we-wake-at-2-3am.md (acrophase ~2-4am, melatonin timing wake-time-anchored per Burgess & Fogg 2008) and with Ch07.17 ("holds high… eases from ~2am"). Reverses an earlier "move peak later" idea, which would have contradicted Ch07.17.
- Ch06.18 ACCEPT AS-IS — prose states no specific figure; SHF supports the direction.
- Ch06.19 ACCEPT AS-IS — source-chase done (WebSearch + Europe PMC verbatim). Desensitisation clause backed by Gerdin 2004 (FASEB J; MT2 desensitisation, supraphysiological doses desensitise longer — rat/cell-model caveat); "more isn't more"/grogginess by Menczel Schrire 2022 (J Pineal Res) + SHF. Citations added to claim-references-sources.md and endnotes-draft.md. Prose unchanged. /book/ untouched.

## [2026-06-21] claim-action | ch03 complete (ch03.14 accept as-is)
Ch03.14 (poor sleep ↔ serious disease): accepted as-is, prose stands, well supported (CDC + NINDS). Ch03 fully resolved (03.1 endnote, 03.14 as-is).

## [2026-06-21] claim-action | ch03.1 -> accept + endnote ("summary plus sources")
CBN "more targeted than CBD": accepted prose, filed endnote to /audit/endnotes-draft.md. Verified refs via Europe PMC: da Silva 2025 (Sleep Med Rev meta-analysis — CBD-only NS, SMD 0.13 p=0.61), Bonn-Miller 2024 (only human CBN RCT), Saleska 2024 (CBN adds nothing to CBD). New house-style convention "summary plus sources" added to CLAUDE.md; worked reference example added to /audit/claim-references-working.md. Box ticked in claim-action-list.md.

## [2026-06-15] audit | ch22 (full run, beats + 6 categories) -> outputs/scratch-pad-ch22.md
## [2026-06-14] audit | ch16 (full run, beats + 6 categories) -> outputs/scratch-pad-ch16.md
## [2026-06-12] audit | ch10 (full run, beats + 6 categories) -> outputs/scratch-pad-ch10.md
## [2026-06-12] audit | ch09 (full run, beats + 6 categories) -> outputs/scratch-pad-ch09.md
## [2026-06-09] audit | ch01 (typos + criticality >1/5) -> /audit/ch01-audit.md
## [2026-06-09] audit | ch02 (typos + criticality >1/5) -> /audit/ch02-audit.md
## [2026-06-09] audit | ch02 re-run (post-revision) -> /audit/ch02-audit.md

## [2026-05-31] build | ch01
Pages created: sleep-deficit, afternoon-dip, compensatory-behaviours, time-in-bed-vs-sleep-quality, sleep-fragmentation, cognitive-impairment-from-sleep-loss, sleep-and-disease, anecdote-author-origin-story, anecdote-reading-to-children (9 pages). index.md and log.md initialised. No prior wiki to search against — all pages are new.

## [2026-05-31] ingest | author-style-notes
Filed to /derived/author-style-notes.md. Updated audit-prompt.md usage note to require reading style notes before proposing any rewrite.

## [2026-05-31] ingest | audit-prompt
Filed chapter audit prompt to /derived/audit-prompt.md. Added usage note advising cross-chapter wiki check before recommending fixes.

## [2026-06-04] derived | program naming
Working name Sleep Builders adopted for the program. Updated wiki/the-program.md (alias + working-name note). Created derived/naming-sleep-builders.md with full rationale, shortlist of alternatives, and content generation usage notes.

## [2026-06-06] edit | ch06-proposed resequence + gap fixes
Final beat order: 1,2,13,5,3,4,8,9,10,11,12,6,7,14,15,16,17,18,19,20. Beats 13+5 (supplement purchase + "more is better") moved to before the science explanation — author bought supplements on minimal knowledge, before any deeper research. Gap fixes: bridge sentence added beat 4→8 (window is long, peak is brief; corrects biology); beat 11 "brief period" replaced with "peak"; bridge added beat 12→6; beat 14 opening rewritten to reconnect reference to supplements. File: /audit/ch06-proposed.md.

## [2026-06-07] audit | ch06-proposed — full six-category review
Beat analysis + six-category review complete. Applied fixes: Beat A (supplement purchase cut from pre-science position), Beat B (circadian mechanism named rather than handwaved), Beat C (supplement payoff clarified — window was sporadic not chronic), Beat D (jet lag + shift work folded into one paragraph), Beat 1 redraft (convergence paragraph), hyperarousal phenomenology added (thoughts looping, stuck in go-mode), missed-window supplement use case reframed as wrong direction, memo metaphor cut (repetition/mixed metaphor). No changes to /book/. All proposals in /audit/ch06-proposed.md; scratch pad at outputs/scratch-pad-ch06.md.

## [2026-06-01] audit | ch07
Beat analysis + six-category review. 12 findings: 3 typos/grammar, 2 over-explain cuts, 2 repetition issues, 2 flow/reorder proposals, 1 weak point, 1 abrupt transition, 1 cross-chapter redundancy (caffeine morning window belongs in ch13 not ch07). Files: /audit/ch07-audit.md, /audit/ch07-proposed.md.

## [2026-05-31] build | ch02–ch25
New pages created (30): sleep-incorporated-metaphor, four-executives, hormone-misalignment, adenosine, melatonin, cortisol, dopamine, sleep-window, calming-activating-systems, vagus-nerve, sleep-stages, circadian-rhythm, the-program, three-program-categories, incremental-habit-change, sleep-tracker, supplements, sleep-environment, caffeine, alcohol-and-sleep, bed-sleep-association, cant-sleep-routine, morning-routine, evening-routine, meditation-and-body-scan, napping, exercise-and-sleep, social-media-and-sleep, hydration-and-sleep, food-timing, blood-sugar-and-cortisol, food-sensitivities, sleep-as-a-system, menopause-exception, sleeping-pills, light-and-sleep, anecdote-mountain-biking, anecdote-boat-trip, anecdote-cbn-experiment, anecdote-recovery-outcomes (40 pages). Updated 4 existing ch01 pages (sleep-deficit, compensatory-behaviours, cognitive-impairment-from-sleep-loss, sleep-and-disease). Updated index.md.


## [2026-06-08] audit | A1 headline 16→12 habits applied to audit/ch09-proposed.md (ch9) and new audit/ch24-proposed.md (ch24)
## [2026-06-08] audit | A2 habit numbering: consolidated proposal audit/a2-chapter-titles-proposed.md (Ch13-24 = Habit 1-12, format "Chapter # - Habit #: Name"); synced ch13/ch24 proposed titles
## [2026-06-08] audit | A3 resolved: keep all 6 phase divider headings as-is (no edits); prose enumeration removal carried by B1 (Ch9)
## [2026-06-08] design | A/C model reconciled: two nervous-system states swapping on a clock → three habit jobs (build calm / stop activating late / regulate clock); prose-only, no per-habit tags; replaces removed "3 categories". Captured in scratchpad design note; updated C1 (clock seed), B1 (gateway), B2, F-Ch25 (recap)
## [2026-06-08] audit | B1 + B2 applied to audit/ch09-proposed.md: 3-categories/6-phase enumeration replaced by A/C gateway (two settings, three jobs, honest bridge); setup-framing omitted per request; Part 4 header reworded to three jobs
## [2026-06-08] design | C1 revised: Ch4 seed now label-free (no coined term), framed underneath the executives; A/C naming held to Ch5 to avoid collision with Wake/Sleep split + front-running autonomic mechanism; wind-up/down kept as permanent gloss, not a second concept
## [2026-06-08] audit | C1 applied: new audit/ch04-proposed.md with label-free two-states/trade-off seed inserted after the "clear messaging" paragraph (unnamed; names arrive Ch5)
## [2026-06-08] design | C2-E2 normalised: lowercase activating/calming in prose; verb form for input-effects (caffeine/curiosity/scrolling activates you), noun for the trainable system; "side" in everyday prose / "system" reserved for Ch18; calm-good fully dissolved in Ch21; copy convention recorded in design note
## [2026-06-08] design | author dislikes "side": C3/C4 reworded to bare activating/calming (verb/adjective forms); convention updated. "side" still in applied B1/B2 (ch09-proposed) + C5 — flagged for decision
## [2026-06-08] design+audit | "side" removed everywhere: trainable-system contexts now "activating/calming system" (verb forms kept for effects). Updated convention + B1/B2/C4/C5/F drafts and the APPLIED audit/ch09-proposed.md gateway
## [2026-06-08] audit | C2-C5 applied: ch05 (names activating/calming on caffeine), ch06 (hyperarousal append), ch07 (cortisol handover cement), ch08 (calm-good dissolved into activating/calming = E1 done). All in -proposed files.
## [2026-06-08] audit | D1+D2 applied: new audit/ch18-proposed.md (A/C lowercased throughout; introduced-as-known via bridge; top-down/bottom-up dissolved to "direction the signal travels"). E2 applied: new audit/ch21-proposed.md (calm-good/hyped-good dissolved). E1 already done via C5 (ch08).
## [2026-06-08] audit | F applied: new audit/ch25-proposed.md (3-categories restatement → three-jobs recap in activating/calming language). G (fitness echo) left unchanged per author.
## [2026-06-08] audit | E-flag resolved: Ch15 not a target (calm-good language not present). Change list complete: A1-A3, B1-B2, C1-C5, D1-D2, E1-E2, F applied; G left per author.
## [2026-06-08] scope | Ch10-24 A/C appends scoped (scratchpad section H). Finding: back half already threaded (executives + explicit A/C in ch10/19/20/23). Real work = casing sweep (ch19/20/23) + ~4 light one-liners (ch13/14/15/16); rest optional/leave. Awaiting author selection.
## [2026-06-08] audit | H applied: casing sweep (ch19/20/23 lowercased) + 4 light A/C touches (ch13 caffeine, ch14 alcohol 4am rebound, ch15 cant-sleep routine, ch16 morning light). New proposed files ch14/15/16/19/20/23. Optionals (ch11/12/22/24) left per decision.

## [2026-06-08] audit | ch09-proposed full audit -> audit/scratch-pad-ch09.md

## [2026-06-08] build | re-ingest ch01–ch25 (full reconciliation)
Re-read all 25 chapters against the wiki after manuscript updates. Key changes captured: (1) program is now TWELVE habits / six phases (was 16); ch13–ch24 are Habit 1–12, titles now "Chapter N - Habit M: Name". (2) activating/calming nervous-system framing is now the spine, seeded unnamed in ch04, named ch05, threaded through to ch25; lowercase prose convention. (3) old "three categories" model replaced by the "three jobs" (build calm / stop activating late / keep clock on time). Actions: DELETED wiki/three-program-categories.md (framing no longer in book; absorbed into calming-activating-systems). REWROTE the-program.md (12 habits, three jobs, habit numbering, app www.app.com.au) and calming-activating-systems.md (promoted to theme; appears_in expanded to 14 chapters). Fixed stale "16 habits" line in sleep-as-a-system.md. Lowercased "Activating/Calming System" → "activating/calming system" across 7 pages to match current convention. Updated index.md (removed categories row; corrected Program + Calming/Activating rows). No new concept pages required — reconciliation, not accumulation. /book/ untouched.

## [2026-06-08] audit | ch09-proposed re-audit (post wiki/chapter update) -> audit/scratch-pad-ch09.md

## [2026-06-08] audit | ch09-proposed resolution update (3-jobs beat rewritten, header aligned) -> audit/scratch-pad-ch09.md

## [2026-06-09] setup | created /derived/content-ideas.md backlog + added schema rule in CLAUDE.md

## [2026-06-08] audit | ch09-proposed tracking+community section reworked (free app headlined, paper as fallback, community emphasised; URL -> www.sleepbuilders.com.au); over-explaining #2 closed
## [2026-06-08] wiki | the-program.md updated: app URL www.app.com.au -> www.sleepbuilders.com.au, free app + community-completion note

## [2026-06-09] query | seed "Sleep Builders" placement eval -> /audit/seeding-sleep-builders-proposed.md
## [2026-06-09] audit | seed "Sleep Builders" name into ch09-proposed (community, L40) and ch25-proposed (L20, free+url)

## [2026-06-10] audit | ch05 read-through -> audit/ch05-readthrough-notes.md (L1 some/most drift, L2 one-of-two+adneonsine typo, L3 ch7 ref VERIFIED, L4 disruptor-list dedup, L5 cope-with-tiredness overreach, L6 "exit isnt willpower" -> Option A chosen, L7 caffeine para). S1 flagged: recommend christening activating/calming in ch04 (label-only) — REOPENS C1/C2 unnamed-in-ch04 decision. Awaiting author decisions 1-4.

## [2026-06-10] design | S2 LOCKED: Sleep Inc concept model. Mission = "a good nights sleep" (output, downstream/not forced); 4 execs (2 wake/2 sleep); aligned to function; CEO guides via Active/Calm/Timing signals (= ch09 three jobs). Supersedes "underneath the executives" layering + the active/calm-BALANCE mission (dial had no slot for Timing). #4 stands, no 5th node. S1 naming question now resolved INSIDE S2. Cautions: sleep stays downstream; signals act on overall system not 1:1; execs stay levers. Recorded in audit/ch05-readthrough-notes.md; S1 annotated as refined-by-S2 (findings intact).

## [2026-06-10] housekeeping | proposal change-set applied into /book/ directly by author; 17 stale chNN-proposed.md drafts archived to audit/archive-proposed-2026-06-10/ (with README). Analysis/findings files retained in audit/ (ch01/02/07-audit, melatonin-onset-audit, scratch-pad-ch06/09, ch05-readthrough-notes). Non-chapter proposals (a2-chapter-titles, seeding-sleep-builders) left in place pending author call. Book = source of truth; future proposals start fresh.
## [2026-06-10] housekeeping | also archived a2-chapter-titles-proposed.md + seeding-sleep-builders-proposed.md (19 drafts total in archive). audit/ now holds only analysis/findings: ch01/02/07-audit, melatonin-onset-audit, scratch-pad-ch06/09, ch05-readthrough-notes.
## [2026-06-10] handoff | wrote audit/CONTINUATION-s2-redraft.md — resumable prompt for the S2 redraft (ch04 rework + S1 naming resolved inside it, ch05 L1-L7, consistency sweep ch06-09/21). Concept locked, wording open. First fork: ch04 top-restructure vs reworked closing beat.

## [2026-06-10] redraft | ch04 -> audit/ch04-proposed-s2.md (S2 model, TOP restructure per author). Mission (good night's sleep, produced not forced) + three signals (Active/Calm/Timing) seeded near top, landed in full at the "clear messaging" beat. Activating/calming christened label-only (S1 resolved). Old ¶69 "underneath... wind up/wind down" rhythm para removed. Cautions a/b/c held. Awaiting author review before ch05 pass.

## [2026-06-10] redraft | ch04 mission beat reworded -> explicit callback to ch3 "uncomfortable truth" ("sleep is something your body does, once conditions are right"). Dropped "Every company makes something / took me 20 years" framing per author; now opens "This company makes only one thing...". Defuses duplication signal (ch02 switch -> ch03 truth -> ch04 mission). Applied to ch04-proposed-s2.md + markup.

## [2026-06-10] redraft | ch04 mission beat finalised: "This company makes only one thing... But you can't place an order directly. That's the uncomfortable truth from Chapter 3..." Dropped redundant "not something you can force". Applied to ch04-proposed-s2.md + markup.

## [2026-06-10] redraft | ch04 three-signals seed finalised per author: "So your job isn't to make sleep... a signal to be active, a signal to be calm, and a signal about timing. Hold those three loosely in your mind for now." Dropped "either", dropped timing gloss "keeping the whole thing on the clock" (flagged), removed italics. Applied to ch04-proposed-s2.md + both markups.

## [2026-06-10] redraft | ch04 seed: restored a light timing gloss per author -> "a signal about timing — when to do things." Applied to ch04-proposed-s2.md + both markups.

## [2026-06-10] redraft | ch04 "clear messaging" beat tone pass: cut signal/messaging repetition, broken 3-item parallelism, stacked metaphors. Final: "...the right signals across the day. Through the day, you call for activity... Through the evening, calm... And timing - the cue that tells active and calm when to switch over. When the three line up, the executives do too." Applied to ch04-proposed-s2.md + markup. FLAG: christening of activating/calming softened to "activity/calm/active" lowercase here - S1 christening point may need confirming for ch05 dependency.

## [2026-06-10] redraft | ch04 christening beat finalised: "Activating — through the day — switched on, ready to go. Calming — through the evening — ... And timing — the cue that tells activating and calming when to switch over." Labels fronted -> resolves S1 christening (activating/calming named here, label-only). Clean chapter written to audit/ch04-proposed.md. Moving to ch05.

## [2026-06-10] redraft | ch05 -> audit/ch05-proposed-s2.md. Book already had L2 typo + L4 list dedup + L5 overreach fix applied. Still proposed: L1 most->some, L6 "exit isn't willpower"->Option A ("way out of the loop isn't forcing it"), L7 caffeine para = clean activating example (removed mid-para christening + orphaned "wind-up from the last chapter"; names now from ch04). Optional L2 logic tighten offered. L3 ch7 ref left (verified).

## [2026-06-10] redraft | ch05 clean -> audit/ch05-proposed.md. Applied: L1 most->some, L2 logic tighten ("one of two things — or both. Either... or..."), L6 Option A, L7 caffeine clean example ("Every cup is activating — a signal that lasts for hours. A cup late in the day reaches well into the evening, exactly when your body needs to be calming."). L3 left. NOTE: /book/ch05.md ends mid-sentence "It just" — preserved faithfully in proposal (flag for author).

## [2026-06-10] redraft | ch05-proposed.md updated to pick up author's new manual ending in /book/ch05.md ("...It just wasn't the whole picture. ... That's a timing problem — and it takes more than one executive to solve it. ... Melatonin is next."). New ending coheres with S2 (names the timing signal + alignment) — no conflict.

## [2026-06-10] build | ch04 + ch05 (S2 reconciliation)
Synced the wiki to the hand-applied S2 manuscript. Touched 5 wiki pages + index. calming-activating-systems: removed "wind up and wind down" from canonical aliases (now descriptive only); rewrote ch04 appears_in (christened label-only, not "seeded unnamed"; old "one simple rhythm / wind up-down" layering gone) and ch05 appears_in (now uses the names as a clean caffeine example, doesn't christen); body now states three jobs = ch04's three signals (Activating, Calming, Timing) turned into action. sleep-incorporated-metaphor: added mission = a good night's sleep (output, produced not forced), CEO can't command sleep/operate executives directly, guides via three signals; +[[Calming and Activating Systems]] link. the-program: three jobs framed as the three ch04 signals turned into daily action. four-executives: executives = the levers the three signals act through; +wikilink. caffeine: ch05 reduced to clean activating-example (half-life/Huberman/blockade detail relocated to ch13 citation — flagged for verification on ch13 pass). index.md rows refreshed. No pages created/deleted — reconciliation only. /book/ untouched.

## [2026-06-10] audit | S2 consistency sweep ch06/07/08/09/21 -> audit/s2-consistency-sweep.md. ch06/07/08/21 cohere with signals-not-balance framing (no change). ch09 structurally fine but three jobs don't visibly = three signals; one suggested edit (add "the three signals from Chapter 4 turned into daily action"). Hygiene flag: ch06/07/08/21 /book/ files carry leftover "audit draft" headers on lines 1-2 (author to strip by hand).

## [2026-06-11] audit | 2-3am melatonin-decline wake-up placement -> /audit/melatonin-2-3am-wakeup-placement.md
## [2026-06-11] audit | corrected melatonin peak time (was "2-3am", now ~midnight-1am per author timeline) in melatonin-onset-audit.md; reversed Clash 1 in melatonin-2-3am-wakeup-placement.md (idea is timeline-consistent); fixed wiki/sleep-window.md (window = steep rise, not peak). ch06 within-chapter check: consistent on the rise; residual error = line 54 "signal has passed its peak" (premature) + ch08 l66 "started to fall" — both already in melatonin-onset-audit Findings 2/3, still unapplied to /book/.
## [2026-06-11] audit | ch06 peak/window disambiguation -> /audit/ch06-proposed.md (full clean redraft; reserves "peak" for melatonin, renames bedtime convergence to "the window", adds felt-window callback + corrected timeline, fixes "passed its peak" supplement error)
## [2026-06-11] audit | ch08 sleep-window timing fix -> /audit/ch08-proposed.md (full clean redraft; "melatonin had already started to fall" -> "the steep rise had passed", ch06 callback). Flagged: /book/ch08 final line truncated ("The biology made sense to").
## [2026-06-11] audit | ch07 2-3am melatonin-decline modifier -> /audit/ch07-proposed.md (full clean redraft; new paragraph after "At 2am the cortisol spike collapses..." — melatonin eases from ~2am, lowers the floor, cortisol fills the gap; melatonin a contributor not a rival cause). wiki/cortisol.md appears_in update

## [2026-06-12] audit | ch11 cortisol front-load -> /audit/ch11-proposed.md (full clean redraft; new framing ¶ opening "What I take and why" makes evening-cortisol the shared selection logic, Ch7 callback in ch09 "You met…" register; trimmed redundant cortisol mentions from PS/ashwagandha/magnesium blurbs). Flagged unresolved in /book/ch11: "For quick reference:" orphan stub, "Why I stopped looking for more" body missing, layering ¶ truncated at "and your tracker".

## [2026-06-12] audit | reconcile proposals vs /book/ — ch04/ch05/ch06/ch07/ch08 + ch11 prose all applied (author reworded in places). Outstanding: ch11 three unfinished spots ("For quick reference:" stub, empty "Why I stopped looking for more" section, sentence truncated at "and your tracker"); ch11-proposed.md now STALE vs applied framing wording; applied proposals (ch06/07/08/11) candidates for archive.

## [2026-06-14] audit | ch15 sequencing -> /audit/ch15-sequencing.md
## [2026-0
## [2026-06-14] audit | ch17 orphan reference "the health retreat version" -> /audit/ch17-health-retreat-reference.md (line 13 callback to an idealized-evening passage that exists nowhere in /book/; nearest analog = ch12:7 "sleep sanctuary"; 3 fix options, recommend Option B align w/ ch12 framing unless a passage was genuinely moved)

## [2026-06-14] audit | ch17 full chapter audit (per derived/audit-prompt.md) -> /audit/scratch-pad-ch17.md. Stage 1 beats: 3 problem beats (L13 re-tread+broken ref, L37/L41/L43 stacked recaps). AGREED w/ author: fold L37 into trimmed L41 ("A clean line to bed. Sleep only. ...occasionally earlier or later depending on sleepiness"), resolves Beat 3. Stage 2 six categories: Contradiction (L19 "no devices"+TV), Cadence x4 (L9/L23/L31/L35), Weak point (L31 unsupported bedtime-consistency science -> citation list), Over-explaining (recaps+L3/L25+L9), Repetition (L19 TV criteria vs ch15 [strongest]; "bed is for sleep" 3-ch; morning-anchor vs ch16; "window" overloaded 3 senses), Abrupt (only internal L23). Typos: L21 spikes, L35 is-little/its.

## [2026-06-14] audit | ch17 edits recorded -> /audit/scratch-pad-ch17.md "APPLY LIST" (line-ordered hand-apply sheet). AGREED: L37 cut + new L41 (fold/trim), L23 core (Lying down means sleep / em-dashes). REVIEWED: L9 (OE4+absorbs Cadence1), L11/L15 (window->gap), L19 Rep1 (cross-ref ch15), L25 (OE3), L35 (Cadence4), L39 (Rep3). PENDING author wording: L13 (sleep-sanctuary ref fix), L19 contradiction ("no phones"), L23 optional Rep2 callback. Carried: L31 unsupported claim -> citation list; index cross-link ch15<->ch17.

## [2026-06-15] audit | ch18 opening cut + verdict merge -> /audit/ch18-opening-verdict.md (cut L12 cliche/echo button; merge doubled verdict L38+L40, keep L38 in place — do NOT move endorsement to front, arc needs L36 proof first)

## [2026-06-15] audit | ch18 expanded -> /audit/ch18-opening-verdict.md (added Finding 2 reframe block L22-30: scope critique + Ch7 two-states callback + capacity-not-content, rejects both aspirin & cognitive-reassurance framings, push-up split folded in; Finding 4 L84 direction fix brain-to-body vs body-to-brain. Contradiction guardrails: foil = "cognitive reassurance" NEVER "safety-signal model"; threat stays cause not lever; two-states callback not re-teach; L78 already carries direction critique)

## [2026-06-15] audit | ch18 proposal renamed -> /audit/ch18-proposed.md (was ch18-opening-verdict.md; consolidated 4 findings: L12 cut, L22-30 reframe expansion, L38+40 verdict merge, L84 direction fix). Note: user said "ch19" — confirmed slip, content is ch18 Meditation.

## [2026-06-15] audit | ch18 full written redraft -> /audit/ch18-proposed-written.md (clean copy of /book/ch18 with all 4 proposed changes applied: L12 cut, L22-30 reframe expansion, L38+40 verdict merge, L84 direction fix). Preserved /book/ truncated final line ("The greatest benefit wasn") as-is.

## [2026-06-15] edit | ch18-proposed-written.md final line completed by author (was truncated "The greatest benefit wasn"); now closes on capacity-not-content payoff + footnote restored. /book/ch18 still carries the truncation.

## [2026-06-15] edit | ch18-proposed-written.md L52 — added disuse cause to calming-system weakness ("weakened from lack of use — a life that's always on rarely gives it a turn — until it can't bring them back"); feeds muscle metaphor, frames behavioural cause without implying fix=more downtime.

## [2026-06-15] edit | ch18-proposed-written.md L58 — added afferent mechanism for attention-to-sensations (vagus runs both ways; attending works the nerve from the sensory side), closes orphan claim + seeds L76-78 body-to-brain. Fixed dropped-word fragment "A long, nerve" -> "A long nerve".

## [2026-06-15] edit | ch18-proposed-written.md L64 — cut cliche tag "That's a different thing entirely."; para now ends on "changing the chemistry that makes quiet possible."

## [2026-06-15] edit | ch18-proposed-written.md style/register sweep vs derived/author-style-notes.md: typos (unique/because/it feels); L60 rewrite (lungs not breathing, dropped "incredibly"); terminology (calming system lc, Wake Executive consistent); duration numerals (5/10-15 min, 30s, 5s); punctuation (em-dashes, stray commas); L58 para break; L62 "regulates and" cut; Chapter 7 callback. Kept "definitely moved the needle" per author (emphasis exception).

## [2026-06-15] audit | ch18 (per derived/audit-prompt.md) Stage 1 beats -> /audit/scratch-pad-ch18.md. Source = ch18-proposed-written.md. 2 problem beats: (1) signal-direction re-explained L82->L84 [+4x cluster L60/82/84/90]; (2) signpost over-promise L44 "why consistency matters" paid off at L70-74. Awaiting confirm before Stage 2.

## [2026-06-15] audit | ch18 Stage 1 fixes applied to ch18-proposed-written.md: beat 1 (L84 redundant restatement cut — already in file), beat 2 (L44 signpost clause "and why consistency is the thing that matters" trimmed).

## [2026-06-15] audit | ch18 Stage 2 six-category review -> /audit/scratch-pad-ch18.md. Contradictions: none (threat/safety + cant-fix-in-moment checked, hold). Cadence: L80 winding tail; L76 trailing space. Weak: L98 absolute claim; vagus/cortisol claims -> citation pass. Over-explaining: L116/118/122 "still training" (trim L118); two-systems re-grounding LEAVE. Repetition: direction cluster (trim L90 echo); muscle motif LEAVE. Abrupt: L76->L78 stutter (fold transition). Wiki note: add ch18 to Cortisol appears_in. 5 recommended edits documented w/ markup; not yet applied.

## [2026-06-15] audit | ch18 applied Contradictions(none)/Cadence/Weak/Over-explaining to ch18-proposed-written.md: L80 tail tightened ("I recommend it for one reason:"), L76 trailing space removed, L98 absolute claim softened, L118 "You have still done the work." cut. Remainder pending instruction: Repetition L90 echo, Abrupt L76 fold.

## [2026-06-15] audit | ch18 applied Repetition + Abrupt to ch18-proposed-written.md: L90 cut "runs the other way. Body to brain" echo -> "The body scan has no words at all"; L76 folded "The next question is which kind." onto the "Aim for sessions." line. All Stage 2 actionable findings now applied (Over-explaining 2 + muscle motif left intentionally; vagus/cortisol claims carried to citation pass).

## [2026-06-15] edit | ch18-proposed-written.md L46 reordered (fix dangling "these two"): now "Your nervous system runs in two broad modes. You already know them — ... since the start. Here's the biology underneath them." Transition check L44->L46->L48->L50->L52 clean (hand-off improved).

## [2026-06-15] audit | ch19 napping -> audit/scratch-pad-ch19.md (beat analysis + 6-category review)

#
## [2026-06-16] au
## [2026-06-23] action-list | ch08 dopamine — decisions applied
- Ch08.6/10/12 (variable-reward desensitisation, contested T5): EDIT + endnote. Hedged at line 21 ("may start to lose out") and line 37 ("the thinking goes, this may recalibrate…"); line 33 (novelty/unpredictability) left as supported mechanism. Author rejected an in-prose concession sentence as off-register; concession + directional evidence moved to endnote (reduced striatal D2 in heavy users; Engineered highs, Addict Behav 2023). -> /audit/ch08-proposed.md + endnotes-draft.md
- Ch08.14 (passive TV, T4 extension): ACCEPT AS-IS + endnote flagging it as a directional inference (Berridge 2007; Addict Behav 2023), no head-to-head study. -> endnotes-draft.md

## [2026-06-23] action-list | ch10 feedback loop — decisions applied
- Ch10.15 (REM/memory, HIGH T2): EDIT. "is where memory consolidation and emotional processing happen" -> "is central to..." (NINDS: memory needs both non-REM and REM). -> /audit/ch10-proposed.md
- Ch10.16 (HRV two-modes, T3 minor): ACCEPT AS-IS + endnote conceding the picture is a simplification but close enough to see habit effects (Shaffer & Ginsberg 2017). -> endnotes-draft.md
- Ch10.21 (Oura most research, T3): ACCEPT + reference endnote with validation citations (Oura Gen3 PSG Sleep Med 2024; Sensors 2024). -> endnotes-draft.md

## [2026-06-23] action-list | ch11 supplements — decisions applied
- Ch11.7 (PS dose/timing, SOURCE): EDIT + endnote. Dose 300-500mg -> ~400mg; "the science says take 30-60 min before bed" -> "taken 30-60 min before bed". Endnote: Monteleone 1992 (400-800mg brain-cortex PS, exercise-stress cortisol). Table PS row -> ~400mg.
- Ch11.10 (Mg L-threonate, SOFTEN T5): EDIT + endnote. "absorbed more effectively / better evidence base" -> "often recommended on the basis that it crosses into the brain more readily"; animal-data + thin-evidence caveat moved to endnote (Mah & Pitre 2021) per author.
- Ch11.11 (Mg dose, NOTE -> upgraded NUMBER/clarity): EDIT + endnote. Web-verified L-threonate dosed by compound: ~2g compound = ~144mg elemental (Magtein). Replaced "150-300mg evening" with form-specific dosing; endnote explains elemental vs compound (Magtein dosing; Sports Research label). Table Magnesium row updated.
- All -> /audit/ch11-proposed.md + endnotes-draft.md

## [2026-06-23] action-list | ch12 sleep environment — decisions applied
- Ch12.9 (temp superlative, T6 author framing): EDIT (Option A) + endnote. "the environmental factor with the most direct connection to sleep quality" -> "wired into the biology of sleep itself - your body has to cool down to fall asleep and to stay there". Endnote quotes Okamoto-Mizuno 2012 (heat/cold -> increased wakefulness, decreased REM & SWS).
- Ch12.10 (16-26C range, NOTE): ACCEPT AS-IS (already framed as popular sources).
- Ch12.11 (core-temp drop, NUMBER/unit): EDIT. "around one to two degrees" -> "around half a degree to a degree Celsius (about one to two degrees Fahrenheit)". Corrects the C magnitude, shows both units.
- -> /audit/ch12-proposed.md + endnotes-draft.md

## [2026-06-23] action-list | ch13 caffeine — decisions applied
- Ch13.6/13.7 (six-hour half-life, NUMBER): EDIT + endnote. "six-hour" -> "roughly five-hour"; "gone in twelve hours / clear by 10pm" -> "ten hours / 8pm"; worked example retimed 10am->3pm->8pm. Lit ~4-5h (EFSA 2015 ~4h; Agboola 2026 ~4h; consensus ~5h). Endnote with EFSA/Agboola/SHF.
- Ch13.8/13.9 (delay first coffee 60-90min, SOFTEN/weak-popular): ACCEPT + endnote. Prose already hedged; endnote states plainly it is popular low-confidence advice, not established science (morning cortisol-caffeine evidence thin/contested).
- -> /audit/ch13-proposed.md + endnotes-draft.md

## [2026-06-23] action-list | ch16 morning routine — decisions applied
- Ch16.11 (movement "amplifies the signal", NOTE/weak-extension): EDIT. "But movement alongside it amplifies the signal." -> "But movement alongside it helps too — exercise is its own gentle cue to the body clock." Drops the unprovable additive "amplifies the light signal" claim; reframes movement as a modest independent circadian cue. Ref MOV1 (T4, weak/extension; "keep modest"). Only change in chapter.
- -> /audit/ch16-proposed.md

## [2026-06-23] action-list | ch18 meditation — decisions applied
- Ch18.21 (trained vagus "suppresses cortisol", SOURCE/extension): EDIT (one word) + endnote. "suppresses" -> "helps turn down" the cortisol response. Endnote concedes the trained-vagus->lower-cortisol st
## [2026-06-25] audit | ch12 temperature section — Stage 1 beat + Stage 2 (6-cat) review; selected fixes applied to audit/ch12-proposed.md; analysis in scratch-pad-ch12.md. Open item: file Haskell 1981 source for new endnote ⟦EN:Ch12.12⟧.

## [2026-06-25] endnote | ch12.15 (near-naked ~29 °C) — wrote summary-plus-sources endnote: Haskell 1981 + Okamoto-Mizuno 2012. Working note in audit/endnotes-draft.md; reader-facing compiled to audit/endnotes-final.md (Chapter 12 group, heading "Where does the 29 °C figure come from?"); source registry audit/claim-references-sources.md updated; prose marker in audit/ch12-proposed.md fixed ⟦EN:Ch12.12⟧→⟦EN:Ch12.15⟧ (12.12–12.14 already assigned). Action item CLOSED.

## [2026-06-25] query | claims-knowledge-base.md — added contested entry for the near-naked ~29 °C figure (Ch12.15); sources Haskell 1981 + Okamoto-Mizuno 2012.
## [2026-06-25] audit | stripped inline ⟦EN:…⟧ prose markers from ch08,10,11,12,13,18,20,22,23,24 proposed files (per no-in-text-marker rule); working-note headers + ch18 author footnote left intact

## [2026-06-25] recovery | audit/ch12-proposed.md was found truncated mid-word (OneDrive partial write) losing Noise+TV; rebuilt in full from context (header + intro/Light + edited Temperature section + verbatim Noise/TV). FLAG: /book/ch12 also corrupted by same sync event (temperature section overwritten with proposal text, middle block missing) — author to restore from OneDrive version history; agent did NOT edit /book/.

## [2026-06-26] derived | KB endnote tagging + 8 content carry-overs -> /derived/claims-knowledge-base.md
Architecture decision: KB is source of truth for all endnotes; endnotes-final.md is a compiled subset. All 46 contested entries converted from <!-- contested --> to <!-- contested --> <!-- endnote --> (bulk sed). 5 standalone <!-- endnote --> markers added for non-contested reference entries (Ch06.19 high-dose melatonin, Ch10.21 Oura, Ch19.5 nap timing, Ch20.18 4h exercise floor, Ch24.24 IgG tests). File truncation (OneDrive cloud-only tail) recovered via Edit tool. 8 substantive content carry-overs from endnotes-draft into KB: Ch03 CBN sources replaced; Ch18 528 Hz Akimoto 2018 added (n=9 caveat); Ch22 George 1975 bladder added; Ch24 Minihane/Calder 2015 added; Ch11 Mg elemental arithmetic note added; Ch24 Altinsoy 2025 brain-fog added; Ch19 nap timing URLs firmed + Mayo added; Ch24 AAAAI URL added. Total tagged: 51 entries (46 contested + 5 standalone). /book/ untouched.

## [2026-06-26] derived | register change — endnotes voice -> neutral encyclopedia
Author decision: endnotes-final.md to use neutral encyclopedia voice, not author-voice. This supersedes the "author-voice" lock set on 2026-06-24. CLAUDE.md updated accordingly (ENDNOTE PRESENTATION STYLE + SUMMARY PLUS SOURCES sections).

## [2026-06-26] endnote | endnotes-final.md compiled in full -> /audit/endnotes-final.md
Full compilation from 51 KB tagged entries into 47 reader-facing notes across 20 chapters in neutral encyclopedia voice. Replaces Ch12-only author-voice draft. 4 pairs of adjacent entries combined into single notes (Ch11 PS cortisol+dose; Ch14 drink-count figures; Ch20 exercise 4h+6h margin; Ch24 sugar crash+cortisol surge). Ch15.22 lux figures flagged within the note as illustrative/unverified (no primary measurement study identified). /book/ untouched.

## [2026-06-26] derived | page-range dashes normalized -> /derived/claims-knowledge-base.md
Replaced 11 distinct citation page-range hyphens with en-dashes (e.g. 37:539–549, 13:298–309, 141:846–850 etc.) across 26 affected lines. Prose ranges (3–7 hours, 25–50 lux, etc.) and DOIs/URLs left untouched. /audit/endnotes-final.md was already clean (compiled with en-dashes). /book/ untouched.

## [2026-06-26] housekeeping | spent files archived -> /audit/archive/
Moved 35 files to /audit/archive/: 17 ch-proposed files (ch05–ch24), ch15-light-lux-proposal.md, 9 audit scratch-pads (ch06/09/14/17/18/19/21/23/24), 8 root scratch-pads (ch06/07/08/12/15/claims-ranking + scratch-pad.md + scratchpad.md), endnotes-draft.md, and the original continuity-coherence-pass.md (superseded by the revised -2026-06-16 version, which was renamed to the canonical path). /audit/ active files: endnotes-final.md, continuity-coherence-pass.md, audit notes, claim-references legacy files. Root is clean.

## [2026-06-26] housekeeping | claim-references files archived -> /audit/archive/
All 6 claim-references working files confirmed safe to archive: every source they contain (14 authors checked by grep) is already present in claims-knowledge-base.md. Files moved: claim-references.md, claim-references-working.md, claim-references-sources.md, claim-references-MED.md, claim-references-MED-working.md, claim-references-MED-sources.md. Unique content lost: verbatim paper quotes (working verification notes) and T1–T6 tier ratings (superseded by KB status/contested markers). /audit/ active files now 16.

## [2026-06-26] schema | CLAUDE.md amended — file map + register update
Added "File map — canonical vs working" section (after Layers and folders) documenting KB as source of truth, endnotes-final.md as compiled subset, archive status of endnotes-draft.md, and legacy status of claim-references files. Updated ENDNOTE PRESENTATION STYLE: "author-voice summary" → "neutral-encyclopedia-voice summary"; working-file reference updated from endnotes-draft.md to claims-knowledge-base.md. Updated SUMMARY PLUS SOURCES: voice changed to neutral encyclopedia; worked example pointer updated to claims-knowledge-base.md.
> lower cortisol + better sleep but is not morning- or baseline-specific (trials mostly breast-cancer patients). Morning-timing logic earlier in the para untouched (cortisol-curve mechanism).
- Ch20.18 (research: finish vigorous 4 h before bed, was SOFTEN): ACCEPT AS-IS + reference endnote. FLAG WITHDRAWN this pass. The 4 h figure is directly supported by Leota et al. 2025 (Nat Commun 16:3297; 14,689 adults / 4.08M person-nights WHOOP data): "exercise bouts ending >=4 hours before sleep onset are not associated with changes in sleep." Stutz 2019 (<=1 h harm, healthy sleepers) now the nuance. Verbatim pinned via Europe PMC (EXT_ID 40234380). Citations logged to claim-references.md (UPDATE note), claim-references-sources.md, endnotes-draft.md.
- Ch20.19 (his safer margin 6 h, NOTE): ACCEPT AS-IS. Already framed as self-experimentation; now sits just beyond a 4 h research floor. No change.
- -> /audit/ch20-proposed.md + endnotes-draft.md

## [2026-06-23] action-list | ch22 hydration — decisions applied
- Ch22.4 (mild dehydration -> cortisol, NOTE): ACCEPT AS-IS + endnote. Prose already modest. Endnote concedes firmest evidence is exercise/heat dehydration (Zaplatosch & Adams 2020, Nutrients; SMD ~1.12); everyday mild dehydration a reasonable extension. No prose change.
- Ch22.7/22.8 (cortisol -> loud bladder signal / night-holding, NOTE/author mechanism): ACCEPT AS-IS + endnote. Sleep-depth->bladder-awareness link well grounded (overnight vasopressin + arousal threshold); cortisol->bladder step is the author's own inference, not demonstrated. No prose change.
- Ch22.12 ("between two and three litres", NUMBER/high): EDIT. "somewhere between two and three litres is a reasonable daily amount" -> "around two litres is usually a reasonable daily amount — a little more if you're active or it's hot". 3 L top end overstated EFSA total-water AI (2.0 L women / 2.5 L men; ~1.5-2 L as drinks). Aligns with the two-litre bottle. No endnote (corrected in text).
- -> /audit/ch22-proposed.md + endnotes-draft.md

## [2026-06-23] action-list | ch23 food timing — decisions applied
- Ch23.13a (protein "steadies blood sugar overnight", SOFTEN/mixed): EDIT (one word) + endnote. "steadies" -> "may help steady". Controlled trials mixed on bedtime macronutrient TYPE in healthy people; protein-for-glycaemic-control is firm mainly for glucose problems (next line already states). Web search this pass: no reputable body picks protein over carbs — Sleep Foundation & Northwestern Medicine recommend a carb+protein COMBINATION and credit complex carbs (not protein) with blood-sugar stability, pairing protein with tryptophan. Validates the book's "both have a case." Endnote adds combination guidance + healthy-vs-glucose nuance. carb->tryptophan half (13b) unchanged.
- -> /audit/ch23-proposed.md + endnotes-draft.md

## [2026-06-23] action-list | ch24 sugar & food sensitivities — decisions applied
- Ch24.11 + Ch24.16/24.17 (sugar->cortisol->2-3am waking, NOTE/extension): ACCEPT AS-IS + ONE shared endnote ⟦EN:Ch24.11-16-17⟧ at end of para 40 (single mechanism). Concedes the chain is a well-reasoned mechanism built from established parts (reactive hypoglycaemia [Stuart 2013; Nutrients 2026] + cortisol counter-regulation + 2am cortisol-melatonin handover), not a directly demonstrated cause. Para 40 already hedges well; no prose change.
- Ch24.20 (food sensitivities "low-grade immune response", SOFTEN/contested): EDIT (hedge) + summary-plus-sources endnote. "generating a low-grade immune response" -> "generating what may be a low-grade immune response". Reconciles para 52 with the book's own contested-tests caveat in para 58. Web search this pass: part-evidenced (non-IgE immune-mediated disorders real; diet->low-grade inflammation established, Calder 2015) / part-contested (individual-sensitivity->immune-response rests on food-specific IgG; no validated test, PMC8625578). Endnote ⟦EN:Ch24.20⟧.
- Ch24.21 (symptoms congestion/fog/fatigue/bloating, SOURCE): ACCEPT AS-IS + reference endnote ⟦EN:Ch24.21⟧ (NHS food intolerance; brain-fog/diet/GI study PMC11857395). Honest caveat: symptoms real but nonspecific; investigate not diagnose; rule out coeliac first. Web search this pass.
- Ch24.22 (culprits gluten/dairy/eggs/soy, SOURCE): ACCEPT AS-IS + reference endnote ⟦EN:Ch24.22⟧. All four (wheat/milk/egg/soy) are FDA major allergens; "most common" framed as illustrative shortlist, not pinned ranking.
- Ch24.24 (reactivity blood tests contested, NOTE): ACCEPT AS-IS + reference endnote ⟦EN:Ch24.24⟧ attaching EAACI (Stapel 2008, "should not be performed") + AAAAI. Strongly backs the book's skepticism. No prose change.
- -> /audit/ch24-proposed.md + endnotes-draft.md
- ** Claim-action-list COMPLETE — all open items (Ch16 onward) worked through; Ch03-Ch15 were already decided/drafted in prior passes. **

## [2026-06-23] audit | endnotes-draft consistency sweep
- Cross-checked all ⟦EN⟧ markers placed in /audit/chNN-proposed.md against endnotes-draft.md: all 20 placed markers have a matching endnote; no orphan markers; no missing endnotes (every action-list "endnote" decision has an entry).
- Reordered: Ch06.19 was out of place (sat between Ch13.8 and Ch18.21) -> moved to chapter order, after Ch03.1. File now runs 03 -> 06 -> 08 -> 10 -> 11 -> 12 -> 13 -> 18 -> 19 -> 20 -> 22 -> 23 -> 24.
- Attach-point completeness: added explicit "Attaches at…" lines to Ch03.1, Ch06.19, Ch08.14 (the three reference/summary endnotes that didn't name a location). Every endnote now self-documents where it attaches + decision type.
- Dedup: source reuse (Engineered highs x2 across Ch08.6/08.14; SHF Caffeine x2 across Ch13.6/13.8) is legitimate — left as-is.
- Noted (not changed): multi-claim marker punctuation varies (Ch08.6/10/12 uses slashes; Ch22.7-8 and Ch24.11-16-17 use hyphens). Each matches its proposed-file marker, so left untouched.

## [2026-06-24] query | fb trial recruitment post + funnel + DM scripts -> filed to /derived/fb-trial-recruitment-post.md

## [2026-06-29] audit | drafted proposal: new Ch9 "What Goes Wrong" synthesis chapter -> /audit/ch09-new-what-goes-wrong-proposed.md (current Ch9 -> Ch10 if accepted)

## [2026-06-29] query | blunted nocturnal melatonin in chronic insomnia -> new KB entry (contested/endnote) in /derived/claims-knowledge-base.md, Ch06 section; cites Hajak 1995, Riemann 2002, Léger 2004

## [2026-06-29] audit | drafted proposal: add sleep-maintenance (blunted overnight melatonin) dimension to Ch06 -> /audit/ch06-melatonin-maintenance-proposed.md (new section + close rework + cortisol transition; resolves universal "not a deficiency" contradiction)

## [2026-06-29] audit | full Ch06 redraft incorporating maintenance dimension -> /audit/ch06-proposed.md (applies Changes 1-3 from ch06-melatonin-maintenance-proposed.md)

## [2026-06-29] query | expanded Ch06 blunted-melatonin KB entry with review-level support (Lack/Micic/Lovato 2023, Scott et al. 2025) + PRM low-excretor caveat -> /derived/claims-knowledge-base.md

## [2026-06-29] audit | added slow-release melatonin passage to /audit/ch06-proposed.md (after maintenance section)
## [2026-06-29] query | new KB entry "Does slow-release melatonin help you stay asleep?" (contested/endnote) -> /derived/claims-knowledge-base.md; cites Lemoine 2007, Wade 2010, Ferracioli-Oda 2013

## [2026-06-29] audit | executive-metaphor cognitive-load pass -> /audit/executive-metaphor-cognitive-load.md (verdict: net reinforcing; key finding M1 = singular vs plural "Wake Executive" referent ambiguity)
## [2026-06-29] audit | executive-metaphor pass — appended marked-up per-chapter paragraph proposals (Ch07, 08, 16, 18, 20) -> /audit/executive-metaphor-cognitive-load.md
## [2026-06-29] audit | executive-metaphor — escalated Ch18 ¶64: cortisol/Wake-Executive doubling (metaphor break, not ambiguity); corrected earlier "no change" call; scope-swept, no other instances -> /audit/executive-metaphor-cognitive-load.md

## [2026-06-29] audit | compiled 2 Ch6 notes (overnight signal low; slow-release) into endnotes-final.md from KB; updated KB blunting entry parenthetical to reflect revised Ch06

## [2026-06-29] audit | ch09 proposal: applied review edits — added "Wake up tired" beat; fixed adenosine front-loading wording; "blunted"->"overnight hold runs low"; dopamine wholesome-content + scrolled-past-window; filled Ch6 ref; wake-time -> 2am; prose/typo cleanup

## [2026-06-29] audit | ch09-new "What Goes Wrong" — full chapter audit (beat analysis + 6 categories) -> outputs/scratch-pad-ch09-new.md; applied C&F1 (varied cadence, "carry you through the night") + C&F4 (trim question/typo) to ch09-new-what-goes-wrong-proposed.md; key flags: WP1 missing named personal moment, overview-vs-breakdown over-explain, sleep-window re-defined vs Ch06

## [2026-06-29] audit | ch09-new edits applied to proposal: WP4 (soften "usually"), WP5 (cut contents-summary line), OE3+WP3 (sleep-window -> 1-line Ch06 recall, circadian aside gone), OE4 (2am hold -> Ch06 callback); closed WP1/WP2/OE1 (author calls), OE2 resolved by C&F1 wording, beat-2 melatonin closed via option 1

## [2026-06-30] audit | part-structure rationalisation -> audit/part-structure-rationalisation-proposed.md; flagged no Part 1, Part 2 marker stranded at bottom of ch02, Part 3 single chapter (ch10), Part 4 "habits" mislabelled (opens with non-habit setup chs); recommended moving P3/P4 boundary to ch14 (P3 The Program=ch10-13, P4 The Habits=ch14-25)
## [2026-06-30] audit | part-structure decision: collapse to 4 parts (Problem / Science / Program ch10-25 / Over to You); cut redundant ch11 three-jobs paragraph (duplicates ch10 L15); add Part 1 heading, move Part 2 marker to top of ch03, Part 5->Part 4. Recorded in audit/part-structure-rationalisation-proposed.md
proposal files archived to audit/archive/.

## [2026-06-30] build | ch09 "What Goes Wrong"
Updated 9 existing wiki pages (hormone-misalignment, four-executives, sleep-window, sleep-deficit, adenosine, sleep-stages, circadian-rhythm, sleep-fragmentation, cortisol, dopamine). Created new page: wiki/waking-at-2am.md (circadian turning point mechanism; ch06 + ch09). index.md updated.

## [2026-07-03] query | fb-trial merged post locked -> derived/fb-trial-recruitment-post.md (Post 1 + Post 2 merge, book mention dropped)
/derived/fb-trial-recruitment-post.md

## [2026-07-03] decision | call platform decided: Zoom/Meet link (not native Messenger group call, not Facebook Live) -> /derived/fb-trial-recruitment-post.md. Rationale: no FB-friend requirement, works for commenters who aren't connections. Fixes: DM 2 now includes an RSVP cutoff date; new DM 2b added (confirm + send Zoom link, sent close to the call date) closing the gap where DM 2 got a yes but no link was ever delivered. Format note + open-decisions list updated.

## [2026-07-03] decision | doctor-question safety-net framing dropped intentionally (author's call) -> /derived/fb-trial-recruitment-post.md annotation updated. Q2 (event/medical) is now the only screen; no restoration as 5th question.

## [2026-07-03] edit | DM 1 full redraft locked in -> /derived/fb-trial-recruitment-post.md. Opener genericised ("your interest"); origin line strengthened ("years of trial and error"); structure split into its own paragraph (check in + build in between + Week 5 wrap-up, six sessions); habits breakdown filled in from Post 2 using canonical marketing-frame verbs per derived/three-pillars-mapping.md — "3 to train your body clock, 3 to build your nervous system, and 6 to remove things wrecking your sleep" (was "settle/calm", now matches the locked frame, not Post 2's own "calm" wording); redundant closing paragraph merged into the cost paragraph (kept new fact: first time running the program; dropped duplicate "no cost"/purpose repeat). Qualifying questions expanded 3->4: dropped "currently working with a doctor," added sleep-amount + time zone. FLAGGED: doctor question removal drops the medical/safety-net framing that question carried — annotation added asking whether to restore it (5th Q, fold into Q2, or accept the drop).

## [2026-07-03] edit | DM 1 tracker/supplements disclosure added -> /derived/fb-trial-recruitment-post.md. New second paragraph: "no cost to join" scoped explicitly (participation free, nothing sold by Ben); tracker + supplements framed as recommended/part of the program (not optional add-ons), bought independently (not from him); hardship exception offered without guaranteeing a workaround ("I'll think about whether a work-around exists"). Closing purpose line ("I just want to see if the program itself works...") relocated to end of this paragraph.

## [2026-07-03] edit | DM 1 structure made explicit -> /derived/fb-trial-recruitment-post.md. "5 weeks, one hour a week" replaced with "5 weeks — an hour each week to learn and build a habit, then a wrap-up session. Six sessions in total" (5 weekly habit sessions + 1 final wrap-up, still inside the 5-week span).

## [2026-07-03] edit | DM 1 tightened -> /derived/fb-trial-recruitment-post.md. Three-pillars restatement (already read in the post) replaced with brief callback ("same three things from the post"). Program structure made definitive: "5 weeks — we come together for one hour each week, and you build the habits in between sessions" (was "about 5-6 weeks, roughly one short session a week"). Flag: file header note still says "5-6 weeks" describing the book's program generally — not yet reconciled with DM 1's firm 5-week trial framing.

## [2026-07-03] edit | Post 1 ("The post (final)") locked in -> /derived/fb-trial-recruitment-post.md. CTA changed to "hear more"; qualifier swapped to Post 2's tighter version (drops explicit specific-event/medical exclusion clause — now screened privately via DM 1 Q2 instead). Posting notes consolidated (stale "book mention" line removed, correct CTA/qualifier notes merged in). "Post 1" heading marked superseded/section-marker only (duplicate of "The post (final)").

## [2026-07-03] query | Post 1 vs Post 2 predicted-response comparison -> appended to /derived/fb-trial-recruitment-post.md. Verdict: Post 1 primary (stronger hook, higher relatability, no self-promo risk); Post 2 fallback. Flagged posting-notes/CTA mismatch under "The post (final)" heading (describes Post 2, not attached text).

## [2026-07-09] audit | ch01/ch02 symptom additions -> ch01-ch02-symptom-additions-proposed.md

## [2026-07-09] audit | ch01 concept 4 (darkest-times severity marker, reduced-severity) added -> ch01-ch02-symptom-additions-proposed.md

## [2026-07-09] audit | ch01 concept 5 ("I wanted it to be one thing" — wish for fixable cause) added -> ch01-ch02-symptom-additions-proposed.md

## [2026-07-09] audit | ch01/ch02 concept 6 (nowhere to turn — split: ch01 isolation + ch02 doctor opener) added; web fact-check of medical claims -> ch01-ch02-symptom-additions-proposed.md

## [2026-07-09] audit | full proposed chapters written -> ch01-proposed.md (C1,C6a,C3a,C5,C4,C2), ch02-proposed.md (C6b,C3b)

## [2026-07-10] housekeeping | archived ch01/ch02/ch06 proposed files -> audit/archive/
Moved 5 spent proposals: ch01-proposed.md, ch01-ch02-symptom-additions-proposed.md, ch02-proposed.md, ch06-proposed.md, ch06-melatonin-maintenance-proposed.md. Confirmed ch06 changes (maintenance dimension, slow-release, cortisol close) already applied+reworded in /book/ch06 (modified 2026-07-01, after the 2026-06-29 proposals). Analysis files (ch01-audit.md, ch02-audit.md) retained in audit/.

## [2026-07-23] audit | ch01 em dash reduction pass -> /audit/ch01-em-dash-pass.md
Found 10 em dashes across 9 paragraphs (L43 has two). Target 2/chapter. Proposed keeping 2 (L15 "day to day — but literally too"; L19 "good thing — it wasn't") and rewording the other 8 (L21, L23, L27, L29, L31, L37, L43x2) to commas/colons/periods. /book/ untouched.

## [2026-07-23] audit | ch02 em dash reduction pass -> /audit/ch02-em-dash-pass.md
Found 24 em dashes across 22 sentences (L79, L95 each a matched pair). Refined process: identified the two punchiest first (L83 "long time — excitement"; L87 "physically present — actually there"), tested reword cost on both — both only minor loss, so both reworded (period break) rather than kept. All other 20 instances reworded too (mix of colon/comma/period, one resumptive-dash sentence at L29 split in two). Result 24 → 0. Flagged but untouched: spaced-hyphen-as-dash instances at L33, L39, L47, L79, L87 — different character, out of this pass's scope.

## [2026-07-23] audit | ch02 em dash pass extended to hyphen-as-dash -> /audit/ch02-em-dash-pass.md
Author instruction: treat spaced hyphens ( - ) as em dashes for this exercise. Added 6 more marks at 5 locations (title hyphen excluded as heading convention, not prose): L33 already covered by prior reword; new rewords for L39 (period), L47 (period, matches "It had to be holistic/flexible" fragment pattern), L79 "ability to handle stress improved - I hadn't" (period), L87 "for years - between... to be - had closed" (commas). Chapter total 30 dash-as-punctuation marks → 0. /book/ untouched.

## [2026-07-23] audit | ch03 em dash reduction pass -> /audit/ch03-em-dash-pass.md
Found 24 marks (20 em dash + 1 en dash treated as dash + 3 hyphen-as-dash, title excluded). Punchiest: L19 "been here before — many times" and L49 "push through it — sleep is optional" — both only minor reword cost, so both reworded. All other 22 reworded (mix of comma/colon/period; L33 two dashes were list-separators not a parenthetical, converted to colon+comma; L63 en dash + hyphen-as-dash bracketing one aside, converted to parentheses). Result 24 → 0. /book/ untouched.

## [2026-07-23] audit | ch04 em dash reduction pass -> /audit/ch04-em-dash-pass.md
Found 31 marks (26 em dash + 5 hyphen-as-dash, title excluded). Punchiest: both on L61 — em dash "anything — just running" and hyphen-as-dash "sleep - I needed a month of them!" — both only minor reword cost, so both reworded. All other 29 reworded (colon for the four executive-label lines L21/23/27/29, treated identically; L39 matched pair converted to parentheses rather than triple comma). Result 31 → 0. /book/ untouched.

## [2026-07-23] audit | ch05 em dash reduction pass -> /audit/ch05-em-dash-pass.md
Found 21 marks (19 em dash + 2 hyphen-as-dash, title excluded). Punchiest: L11 "did the maths - seven cups a day" and L63 "Adenosine is sleep pressure — the force that makes you want to sleep" — both only minor reword cost, so both reworded. All other 19 reworded (mostly comma/colon). Result 21 → 0. /book/ untouched.

## [2026-07-23] audit | ch06 em dash reduction pass -> /audit/ch06-em-dash-pass.md
Heaviest chapter yet: 39 marks (38 em dash + 1 hyphen-as-dash, title excluded; L67 alone had five). Punchiest: L19 "doesn't force sleep — it enables it" and L57 "evidence is thin — thirteen extra minutes" — both only minor reword cost, so both reworded. All other 37 reworded; L39's three-dash cascading sentence bundled into parentheses rather than a 1:1 swap (would have left five commas in a row). Result 39 → 0. /book/ untouched.

## [2026-07-23] audit | ch07 em dash reduction pass -> /audit/ch07-em-dash-pass.md
Found 28 marks (24 em dash + 4 hyphen-as-dash, title excluded). Punchiest: L45 "Not a flaw in you — cortisol, still high" and L59 "Not intentionally — the technology doesn't set out to ruin sleep" — matching denial-then-explanation beats, both only minor reword cost, so both reworded. All other 26 reworded; L63's hyphen-bracketed "- cortisol -" converted to parentheses as a true parenthetical. Result 28 → 0. /book/ untouched.

## [2026-07-23] audit | ch08 em dash reduction pass -> /audit/ch08-em-dash-pass.md
Found 24 marks (22 em dash + 2 hyphen-as-dash, title excluded; L25 alone had four). Punchiest: L9 "something had changed — I wasn't more tired" (opening irony) and L69 "understanding — it's necessary, but it isn't sufficient" (closing thesis) — both only minor reword cost, so both reworded. All other 22 reworded (mostly colon/comma, several matched pairs to parentheses). Result 24 → 0. /book/ untouched.

## [2026-07-23] audit | ch09 em dash reduction pass -> /audit/ch09-em-dash-pass.md
Found 22 marks (21 em dash + 1 hyphen-as-dash, title excluded; L34 alone had four). Punchiest: L52 "You weren't unlucky — you scrolled through your own window" (callback to ch08's closing line) and L82 "Misaligned — four executives arriving at bedtime" (chapter thesis) — both only minor reword cost, so both reworded. All other 20 reworded. Result 22 → 0. /book/ untouched.

## [2026-07-23] audit | ch10 em dash reduction pass -> /audit/ch10-em-dash-pass.md
Found 14 marks (11 em dash + 3 hyphen-as-dash; two heading en dashes excluded as heading convention, not prose). Punchiest: L37 "becomes undeniable — not "I think I feel better", but "something has definitely shifted"" and L43 "What matters isn't how — it's that you do it" — both only minor reword cost, so both reworded. All other 12 reworded. Result 14 → 0. /book/ untouched.

## [2026-07-23] audit | ch11 em dash reduction pass -> /audit/ch11-em-dash-pass.md
Found 25 marks (21 em dash + 2 en dash + 2 hyphen-as-dash, title/heading excluded). Punchiest: L54 "get this right — with one exception" and L72 (en dash) "Start simple – just focus on total hours of sleep" — both only minor reword cost, so both reworded. All other 23 reworded, several matched pairs to parentheses. Result 25 → 0. /book/ untouched.

## [2026-07-23] audit | ch12 em dash reduction pass -> /audit/ch12-em-dash-pass.md
Found 16 marks (14 em dash + 2 en dash, title excluded). Five additional en dashes flagged but excluded as numeric ranges (dosage figures, reference table) rather than rhetorical dashes — different typographic function, out of scope. Punchiest: L44 "simple as possible — the minimum number of supplements for the maximum benefit" and L52 (en dash) "little routine – finish dinner, take my plate, get my supplements. Done." — both only minor reword cost, so both reworded. All other 14 reworded. Result 16 → 0. /book/ untouched.

## [2026-07-23] audit | ch13 em dash reduction pass -> /audit/ch13-em-dash-pass.md
Found 29 marks (26 em dash + 1 en dash + 2 hyphen-as-dash, title excluded). Punchiest: L35 "your bed climate" (chapter's defining phrase, reused later) and L61 hyphen-as-dash "Boom - wide awake" — both only minor reword cost, so both reworded. All other 27 reworded. Result 29 → 0. /book/ untouched.

## [2026-07-23] audit | ch14 em dash reduction pass -> /audit/ch14-em-dash-pass.md
Found 26 marks (21 em dash + 5 en dash, title/heading excluded). Punchiest: L12 "Coffee — not the problem" (echoes ch05's colon version of the same line) and L60 "moved the needle — noticeably" — both only minor reword cost, so both reworded. All other 24 reworded; L24's three-beat tricolon ("Tired... Wired... Groggy...") converted consistently to colons to preserve the parallel rhythm. Result 26 → 0. /book/ untouched.

## [2026-07-23] audit | ch15 em dash reduction pass -> /audit/ch15-em-dash-pass.md
Found 20 em dash marks, title excluded, no en dash or hyphen-as-dash this chapter. Punchiest: L29 "tiredness behind a hangover — not sleep you never got, but recovery the night never finished" and L47 "a hobby — you can't ask a baker not to taste his pastries" — both only minor reword cost, so both reworded. All other 18 reworded. Result 20 → 0. /book/ untouched.

## [2026-07-23] audit | ch16 em dash reduction pass -> /audit/ch16-em-dash-pass.md
New heaviest chapter: 41 marks (40 em dash + 1 hyphen-as-dash; L66 alone had four). Two marks excluded as non-rhetorical: numeric lux ranges in the footnote, and a mid-text "Chapter 7 - Cortisol" title citation (same convention as a heading hyphen). Punchiest: L34 "protect what the bed means — and that means getting out of it" (chapter thesis) and L58 "I still use it — though these days I rarely need it" — both only minor reword cost, so both reworded. All other 39 reworded, many matched pairs to parentheses. Result 41 → 0. /book/ untouched.

## [2026-07-23] audit | ch17 em dash reduction pass -> /audit/ch17-em-dash-pass.md
Found 17 em dash marks; heading en dash and title hyphen excluded as heading convention. Punchiest: L28 "Keen became — I don't want to miss it" (three-step escalation payoff) and L46 "switched on hard — on purpose, early" — both only minor reword cost, so both reworded. All other 15 reworded. Result 17 → 0. /book/ untouched.

## [2026-07-23] audit | ch18 em dash reduction pass -> /audit/ch18-em-dash-pass.md
Found 16 marks (14 em dash + 2 en dash forming a matched pair, title excluded). Punchiest: L9 "exhausted but wide awake" causal payoff and L23 (en dash pair) "this is real life" aside — both only minor reword cost, so both reworded. All other 14 reworded. Result 16 → 0. /book/ untouched.

## [2026-07-23] audit | ch19 em dash reduction pass -> /audit/ch19-em-dash-pass.md
New record: 62 em dashes, by far the heaviest chapter in the book (L65 alone had five, L123 had four). Heading en dash and a numeric-range en dash ("10–15 minutes") excluded. Punchiest: L63 "the lungs are unique — the only organ you can take off autopilot" and L115 "not trying to feel calm — you are doing the work" — both only minor reword cost, so both reworded. All other 60 reworded, mostly colon/comma/parentheses depending on whether the dash framed an aside or an explanation. Result 62 → 0. /book/ untouched.

## [2026-07-23] audit | ch20 em dash reduction pass -> /audit/ch20-em-dash-pass.md
Found 14 em dash marks, title excluded, no en dash or hyphen-as-dash this chapter. Punchiest: L33 "almost beside the point — the rest was already happening" and L39 "If you don't sleep — even better" — both only minor reword cost, so both reworded. All other 12 reworded. Result 14 → 0. /book/ untouched.

## [2026-07-23] audit | ch21 em dash reduction pass -> /audit/ch21-em-dash-pass.md
Found 26 marks (25 em dash + 1 en dash, title excluded). Punchiest: L8 "not a flaw in the system — that's the point" (opening reframe) and L26 "intensity and the timing — and nobody told you" (chapter thesis) — both only minor reword cost, so both reworded. All other 24 reworded. Result 26 → 0. /book/ untouched.

## [2026-07-23] audit | ch22 em dash reduction pass -> /audit/ch22-em-dash-pass.md
Found 30 marks (27 em dash + 3 en dash; heading en dash and title hyphen excluded). Punchiest: L38 matched pair "behaviour change — before anything else —" (the chapter's one non-negotiable instruction) and L44 "not fighting the platform — you're redirecting it" — both only minor reword cost, so both reworded. All other 28 reworded. Result 30 → 0. /book/ untouched.

## [2026-07-23] audit | ch23 em dash reduction pass -> /audit/ch23-em-dash-pass.md
Found 17 em dash marks, heading/title excluded, no valid en dash or hyphen-as-dash this chapter. Punchiest: L13 "doesn't fail in one go — it gets quietly undermined" (thematic statement) and L35 "removes a source of friction — and removing friction is the whole point of Phase 6" (ties back to phase purpose) — both only minor reword cost, so both reworded. All other 15 reworded. Result 17 → 0. /book/ untouched.

## [2026-07-23] audit | ch24 em dash reduction pass -> /audit/ch24-em-dash-pass.md
Found 10 marks (8 em dash + 2 en dash, title excluded). Punchiest: L15 "cool down while it's generating heat — the activating system running" (central paradox) and L27 "protein wins — the safer choice" — both only minor reword cost, so both reworded. All other 8 reworded. Result 10 → 0. /book/ untouched.

## [2026-07-23] audit | ch25 em dash reduction pass -> /audit/ch25-em-dash-pass.md
Found 31 marks (29 em dash + 2 hyphen-as-dash, title excluded; L36 and L40 each had four). Punchiest: L40 "assume you woke to use the bathroom — but often the cortisol surge comes first" (assumption-overturning reveal) and L64 "cutting down manageable — and cutting down made the sleep better still" (closing-loop line for the 12th and final habit) — both only minor reword cost, so both reworded. All other 27 reworded; L58's three-clause sentence split into two rather than a third comma. Result 31 → 0. /book/ untouched.

## [2026-07-23] audit | ch26 em dash reduction pass -> /audit/ch26-em-dash-pass.md
Final chapter. Found 12 em dash marks, heading/title excluded, no valid en dash or hyphen-as-dash. Punchiest: L15 matched pair "bad nights still come — they always will — but they stop defining you as a bad sleeper" (candidate for best line in the book) and L29 "a big rock to lean on — it was amazing she'd stuck with me" (the book's most personal moment) — both only minor reword cost, so both reworded. All other 9 reworded. Result 12 → 0. /book/ untouched.

## [2026-07-24] audit | colon rebalance pass, batch 1 (ch02–ch06) -> /audit/chNN-em-dash-pass.md
Follow-up to the em dash pass: author flagged that colon had become the new default replacement (~33% of all dash conversions book-wide). Re-reviewed each colon in ch02–ch06, kept it only where it does real work (genuine 3+-item list, or a deliberate quoted/thesis line), converted the rest to comma-joins or period-splits. Net-new colon rate (colons introduced by the dash rework, excluding colons already in the original book text): ch02 4/26, ch03 4/20, ch04 3/18 (+4 structural glossary-style colons for the executive labels, treated as a distinct case), ch05 2/17, ch06 0/24. Each file has a "Rebalance pass" section appended. /book/ untouched.

## [2026-07-24] audit | colon rebalance pass, batch 2 (ch07–ch11) -> /audit/chNN-em-dash-pass.md
Continued sequentially. ch07 was the worst offender in the book at 12/20 (60%) net-new colons, reduced to 3/20 (15%). Others: ch08 8/15→3/15 (20%), ch09 4/12→2/12 (17%), ch10 9/13→3/13 (23%, smallest chapter but highest original ratio besides ch07), ch11 9/18→3/18 (17%). Same method: kept colon only for genuine lists/quotes/deliberate lines, rest converted to comma or period. /book/ untouched.

## [2026-07-24] audit | colon rebalance pass, batch 3 (ch12–ch16) -> /audit/chNN-em-dash-pass.md
Continued sequentially. ch12 7/12 (58%)→2/12 (17%), ch13 13/24 (54%)→5/24 (21%), ch14 10/19 (53%)→4/19 (21%), ch15 8/14 (57%)→2/14 (14%), ch16 13/22 (59%)→2/22 (9%, heaviest chapter in the book by raw dash count, now the lowest colon-carryover ratio). ch16 kept one colon for a genuine four-item list (The Simpsons, Family Guy, Archer, South Park) and one introducing a quoted question; all other instances converted to comma or period. Same method throughout. All five files verified programmatically (net-new colon count = colons in reworded text minus colons already present in the original quoted excerpt); one miscount caught and fixed in ch12 (L38 had been left as a colon despite the note claiming it was converted). /book/ untouched.

## [2026-07-23] audit | em dash reduction pass complete, ch01–ch26
Full-book pass finished. Every chapter from ch03 onward landed at 0 (ch01 kept 2, ch02–ch26 all reworded to 0) — no instance anywhere in the book cleared the "real/major punch cost" bar to justify keeping. Heaviest chapters: ch19 Meditation (62 marks, an outlier), ch16 Can't Sleep Routine (41), ch06 Melatonin (39). Lightest: ch15 Alcohol (20, no en dash or hyphen-as-dash at all). Consistent exclusions applied throughout: title/heading hyphens and en dashes, numeric ranges (dosages, lux, minutes), and one mid-text chapter-title citation (ch16 L28). All 26 proposals filed in /audit/ as chNN-em-dash-pass.md. /book/ untouched throughout.
## [2026-08-21] query | fb-trial post: added transparent motive-first intro (research frame) to disarm skepticism -> derived/fb-trial-recruitment-post.md
## [2026-08-21] query | fb-trial post: final tweaks locked (opener reworked, timespan/research repetition trimmed) -> derived/fb-trial-recruitment-post.md

## [2026-09-24] audit | thesis sweep batch 1 (ch01–04): misaligned→fitness, 27 extracts, groups A–D -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis sweep batch 2 (ch05–09): 23 extracts added -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis sweep batch 3 (ch10–13): 18 extracts added -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis sweep batch 4 (ch14–19): 30 extracts added -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis sweep batch 5 (ch20–26 + endnotes/wiki/derived/images): 22 extracts + whole-book findings -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis: sleep-fit canonical definition + "activated is not physically active" line agreed; A/C terms retained -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis decision 1: one-liner = "Not broken, just not well trained." (ch04 L67 + ch19 L29)
## [2026-09-24] audit | thesis decision 2: diagnosis vocab — misaligned only; regulated/balance/fault -> training words
## [2026-09-24] audit | thesis decision 3: broken = sleep only; fix = wrong-approach vocab, goal/result uses -> build/train
## [2026-09-24] audit | thesis decision 4: ch26 L35 close -> "And you have the training program to align the four executives..."
## [2026-09-24] audit | thesis proposals ch03 (8 edits) + ch04 (7 edits, 2 new paras) -> audit/ch03-thesis-proposed.md, audit/ch04-thesis-proposed.md
## [2026-09-24] audit | ch03/04 review: ch03 L25 left unaltered; ch04 L65–67 approved; ch04 new sleep-fit paras parked until full review
## [2026-09-24] audit | clean full-chapter copies for Obsidian diff/merge: audit/ch03 - The Uncomfortable Truth (thesis clean).md, audit/ch04 - Sleep Incorporated (thesis clean).md
## [2026-09-24] query | continuation prompt for thesis pass -> derived/continuation-prompt-thesis-fitness.md
## [2026-09-24] audit | thesis proposals ch09 (2 edits: L82 colon, L84 handover in training words; identity labels raised) -> audit/ch09-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch09 9-B (L84 handover) approved
## [2026-09-24] audit | thesis proposals ch19 (4 edits: L29 one-liner payoff, L41 fix->rebuild, L55 balance->take its turn, L129 regulating->training) -> audit/ch19-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch19 19-A to 19-D approved
## [2026-09-24] audit | thesis proposals ch26 (5 edits: L9 Ch03 echo, L17 fix->sleep fit, L29/L33 em dashes, L35 Decision 4 close) -> audit/ch26-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch26 26-B revised to author's wording ("doesn't improve your sleep")
## [2026-09-24] audit | thesis decision 5: 'sleep fit' not coined; simple language. Ch03 3-D/3-E reworded, Ch04 parked definition dropped (activated line still parked); sweep + continuation prompt updated
## [2026-09-24] audit | ch26 26-A to 26-E approved
## [2026-09-24] audit | thesis proposals ch02 (1 edit: L41 fix->work; L39/L47/L67/L69/L89/L99 reviewed, no change) -> audit/ch02-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch02 2-A approved
## [2026-09-24] audit | thread check: 'just a bad sleeper' -> trainable; mapped, no proposal breaks it; Ch01 L31 callback gap noted -> audit/thesis-fitness-sweep.md
## [2026-09-24] audit | thesis decision 6: labels describe the sleep, not the person (poor/good sleeper shorthand replaced; rejecting uses kept)
## [2026-09-24] audit | ch09 9-C/9-D added (L62, L66 labels, Decision 6) + clean copy updated
## [2026-09-24] audit | ch05 reviewed, no thesis changes (L59 'fix' is the not-one-thing line)
## [2026-09-24] audit | thesis proposals ch06 (6 edits: L27 regulated->trained, L29/L33/L49 labels, L37 set->trained, L61/L63 fix) -> audit/ch06-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch06 6-A to 6-F approved; ch09 9-C/9-D approved
## [2026-09-24] audit | thesis proposals ch07 (3 edits: L19 regulated->trained, L43 everything->much of, L51 label) -> audit/ch07-thesis-proposed.md + clean copy; thread note corrected (busy mind called back at ch07 L9/L45)
## [2026-09-24] audit | ch07 7-A to 7-C approved
## [2026-09-24] audit | thesis proposals ch08 (1 edit: L17 regulation) -> audit/ch08-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch08 8-A approved
## [2026-09-24] audit | thesis proposals ch10 (2 edits: L5 'I wasn't the problem', L13 fault->both can be trained) -> audit/ch10-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch10 10-A ('I wasn't the problem') + 10-B approved
## [2026-09-24] audit | thesis proposals ch11 (2 edits: L16 one thing at a time, L46 balancing->moves between) -> audit/ch11-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch11 11-A/11-B approved
## [2026-09-24] audit | thesis proposals ch12 (1 edit: L62 whole supplement strategy) -> audit/ch12-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch12 12-A approved
## [2026-09-24] audit | thesis proposals ch13 (1 edit: L49 fixed my insomnia -> rebuilt my sleep) -> audit/ch13-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch13 13-A approved
## [2026-09-24] audit | ch14 reviewed, no thesis changes (L6 'single habit most likely to be disrupting' = biggest disruptor, balanced by L60 'never the whole problem')
## [2026-09-24] audit | thesis proposals ch15 (1 edit: L33 label + its) -> audit/ch15-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch16 reviewed, no thesis changes (conditioning + repetitions already on-thesis)
## [2026-09-24] audit | ch17 reviewed, no thesis changes (L40 broken rule kept; morning walk literal movement, no fitness analogy)
## [2026-09-24] audit | thesis proposals ch18 (1 edit: L45 regulated -> trained to come back down) -> audit/ch18-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch19 already proposed/approved earlier this session
## [2026-09-24] audit | ch20 reviewed, no thesis changes (calming-system training sessions already on-thesis)
## [2026-09-24] audit | ch15 15-A + ch18 18-A approved
## [2026-09-24] audit | thesis proposals ch21 (2 edits: L40 regulated->calmest, L62 active-but-calm line; L20-22 reviewed, no analogy added per framing rule) -> audit/ch21-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch21 21-A/21-B approved
## [2026-09-24] audit | thesis proposals ch22 (1 edit: L36 label) -> audit/ch22-thesis-proposed.md + clean copy
## [2026-09-24] audit | ch23 reviewed, no thesis changes (L13 'small things stacking' already on-thesis; fix uses everyday/critique; L23 'Just like a normal person' kept as voice)
## [2026-09-24] audit | ch24 reviewed, no thesis changes (L27 glucose regulation = physiology; L29-33 alignment fine)
## [2026-09-24] audit | ch25 reviewed, no thesis changes (L32 dysregulation kept per Decision 2; L64 'wasn't one thing fixing the other' = not-one-thing critique, kept). Continuity flag: L68 'Twenty-four chapters' vs ch25
## [2026-09-24] query | continuation prompt status update -> derived/continuation-prompt-thesis-fitness.md
## [2026-09-24] audit | ch22 22-A approved
## [2026-09-24] audit | ch22 22-A approved

## [2026-09-24] audit | em dash passes ch12-ch26 applied to clean copies -> audit/chNN - Title (thesis clean).md
Updated existing thesis-clean copies (ch12,13,15,18,19,21,22,26); created new clean copies from /book/ for ch14,16,17,20,23,24,25 (no thesis changes). Em dashes 0 in all. Kept by convention: Phase/Part heading en dashes, numeric ranges (ch12, ch16 footnote, ch19 L71). Extra fix not in pass file: ch23 L21 "matters — which" -> "matters, which". Some pass entries were no-ops where thesis edits had already reworded the sentence (ch19, ch21, ch22, ch26). /book/ untouched.
## [2026-09-24] audit | verified: all thesis proposals (ch02-ch26) already applied in /book/ by author; only parked ch04 paragraphs absent
## [2026-09-24] audit | parked ch04 'activated isn't physically active' line dropped; item closed. ch24 L13 unchanged
## [2026-09-24] audit | busy-mind callback gap closed: author to insert 'And it wasn't just how I was built.' at ch19 L29 by hand
## [2026-09-24] audit | ch25 L68 chapter count updated by author; item closed
## [2026-09-24] audit | wiki thesis update part 1: sleep-as-a-system.md rewritten as thesis page; hormone-misalignment.md, sleep-incorporated-metaphor.md, calming-activating-systems.md updated (Decisions 1-6)
## [2026-09-24] audit | wiki thesis update part 2: label/diagnosis-word sweep across 15 pages (adenosine, circadian-rhythm, compensatory-behaviours, cortisol, hydration-and-sleep, sleep-fragmentation, sleep-window, waking-at-2am, sleep-tracker, anecdote-recovery-outcomes, the-program, meditation-and-body-scan, exercise-and-sleep, melatonin, vagus-nerve); physiological 'regulation' left as is
## [2026-09-24] audit | index.md updated (sleep-as-a-system = thesis; misalignment, metaphor, calming/activating rows)
## [2026-09-24] audit | derived/continuation-prompt-program-structure.md: note that Jun 2026 Fitness Analogy demotion is reversed
## [2026-09-24] audit | archived all 47 .md files from /audit/ root -> audit/archive/2026-09-24/ (incl. endnotes-final.md, continuity-coherence-pass.md, thesis-fitness-sweep.md)

## [2026-09-25] edit | fb-trial post: para 2 now opens "It was a long process to find what worked and what didn't, but now I'm really curious..." -> derived/fb-trial-recruitment-post.md

## [2026-09-25] edit | fb-trial post: para 2 reworded ("It took a long time to figure out what actually helped...") -> derived/fb-trial-recruitment-post.md
## [2026-09-25] derived | three-pillars-mapping.md: Ch16 Can't sleep routine moved Remove disrupters -> Train your body clock (author decision), split now 3/3/6 matching fb post
## [2026-09-25] audit | food timing move (ch24 -> ch16) renumber analysis -> audit/food-timing-move-renumber-proposed.md (9 headings, 11 in-text refs incl 4 already stale, 3 wording, 14 endnotes incl 7 already stale)
## [2026-09-25] audit | phase restructure decided (P2 caffeine/alcohol/food; P3 can't-sleep/morning/evening; P4 meditation/napping/exercise; P5 social/hydration/sugar; Phase 6 removed) -> section G added to audit/food-timing-move-renumber-proposed.md; endnotes+wiki deferred
## [2026-09-25] audit | clean copies for food-timing move + phase restructure -> audit/clean-food-timing-move/ (14 chapters, 31 edits; original filenames kept, headings renumbered; endnotes/wiki deferred). /book/ untouched.
## [2026-09-25] audit | verified food-timing move merged in /book/: all 31 edits present, no stale Phase 6 / old refs; all in-text chapter refs point correctly. Open: ch20 L7 'eighteen chapters in' -> 'nineteen'; filenames ch16-ch24 still carry old habit numbers
## [2026-09-25] query | continuation prompt for endnotes + wiki renumbering -> derived/continuation-prompt-renumber-endnotes-wiki.md
## [2026-09-25] audit | endnotes renumber (title-mapped; Food Timing section moved to Ch16 after Alcohol; L107 alcohol ref Ch14 -> Ch15) -> audit/endnotes (renumbered clean).md (14 changes; /book/ untouched)
## [2026-09-25] build | wiki + index renumber for food-timing move (single-pass map ch24->16, ch16-23 -> +1): 127 refs across index.md + 24 wiki pages; appears_in / index lists re-sorted; the-program.md rewritten to 5 phases; food-timing row moved after alcohol in index; sleep-tracker "Habit 1" error fixed
## [2026-09-25] build | derived renumber: three-pillars-mapping.md (27 refs, sections reordered, summary table rebuilt to 5 phases), compile-docx-prompt.md (file lists -> current filenames), reader-feedback-brief.md (meditation Ch 18 -> Ch 20); CLAUDE.md file map updated for archived endnotes-final / continuity-coherence-pass
## [2026-09-25] audit | verified endnotes merge: book/endnotes.md has a leftover duplicate Food Timing note under a mislabelled "Chapter 25" heading plus the old "Chapter 24 — Sugar" heading (L645-663). Corrected clean copy re-issued -> audit/endnotes (renumbered clean).md (remove 18 lines; 47 notes)
## [2026-09-25] build | claims-knowledge-base.md renumbered to match endnotes: 11 refs (9 headings + 2 "See Chapter" cross-refs), Food Timing section moved to Ch16 after Alcohol; header pointer -> book/endnotes.md; per-chapter endnote placement checked against endnotes
## [2026-09-25] audit | archived audit/food-timing-move-renumber-proposed.md and audit/clean-food-timing-move/ -> audit/archive/
## [2026-09-25] audit | re-verified endnotes after reported merge: book/endnotes.md (mtime 03:31 UTC) still 730 lines with duplicate Food Timing note + stale 'Chapter 24 — Sugar' heading; corrected clean copy re-issued -> audit/endnotes (renumbered clean).md
## [2026-09-25] audit | verified endnotes merge complete: book/endnotes.md 712 lines, 47 notes, 21 chapter headings in order (Food Timing at Ch16), no duplicates; Ch05 alcohol ref = Chapter 15. Food-timing renumber closed.

## [2026-09-29] audit | humanizer clean copies (ch01-ch26) -> /audit/chNN-humanizer-clean.md

## [2026-10-13] audit | registry: removed unsourced 40-60% prevalence figure from ch04 menopause entry (Cintron 2017 measures HRT effect, not prevalence)
## [2026-10-13] audit | registry: corrected Lok 2019 J Pineal Res volume 66 -> 67 (verified via Crossref)
## [2026-10-13] audit | registry: Roenneberg 2012 link corrected (was Zhang 2020 Sleep zsaa076) -> doi 10.1016/j.cub.2012.03.038 (verified, RUG portal); book/endnotes.md ch05 needs same fix in clean copy
## [2026-10-13] audit | endnote coverage: approved Ch1-6 drafts saved -> audit/endnotes-coverage-working.md
## [2026-10-14] audit | ch07 cortisol/dopamine split (4 paras) -> audit/ch07-cortisol-dopamine-clean.md
## [2026-10-14] audit | ch07 clean copy revised (urgency framing, 2 edits); ch08 clean copy (2 edits) -> audit/ch08-dopamine-clean.md
## [2026-10-14] audit | endnote coverage: Ch7 approved drafts saved -> audit/endnotes-coverage-working.md
## [2026-10-14] audit | handover prompt for Phase 2 from Ch8 -> audit/handover-phase2-ch08.md

## [2026-10-14] audit | ch08 clean copy: added edit 3 ("minus the cortisol" -> "with little of the cortisol")
## [2026-10-14] endnotes | ch08 approved and saved to working file (1 pointer, 1 revised, 1 new note); KB: ch08 provocative entry revised, novelty entry added
## [2026-10-14] audit | ch09 unranked-claims skim; clean copy created (edit 1: curiosity line)
## [2026-10-14] endnotes | ch09 notes saved (5 pointers, 1 new note: melatonin decline / early wake, Lack 1996); KB ch09 section added
## [2026-10-14] audit | ch09 clean copy edit 2 ("Often, this is adenosine...")
## [2026-10-14] audit | ch09 clean copy edit 3 ("a shallow night"); ch09 complete
## [2026-10-14] audit | ch10: ranked claim dropped (Ben); clean copy created (massage line softened)
## [2026-10-14] audit | ch11 clean copy created (staging-error paragraph rewritten to match validation studies)
## [2026-10-14] endnotes | ch11 approved and saved (3 new notes: efficiency, deep sleep, tracker accuracy); KB ch11 entries tagged, staging entry revised with 4 new sources
## [2026-10-14] audit | ch12 clean copy created (2 ashwagandha edits)
## [2026-10-14] endnotes | ch12 form + ashwagandha notes approved and saved; KB sources fixed (Pardo 2021, Lindberg DOI) and KSM-66 trials added; magnesium clause pending
## [2026-10-14] endnotes | ch12 complete: magnesium note revised (Abbasi 2012 clause); Held 2002 dropped (results unverifiable)
## [2026-10-14] audit | ch12 clean copy edit 3 (magnesium evidence line); magnesium note wording updated
## [2026-10-14] audit | ch13 clean copy created (edit 1: vivid-dreams line hedged)
## [2026-10-14] endnotes | ch13 approved and saved (4 new notes: light, temp range, REM thermoregulation, noise; 2 TV pointers); KB updated (Mason 2022, Basner 2011 replaces Munzel, temp range sourced)
## [2026-10-14] endnotes | ch14 approved and saved (3 new notes: caffeine mechanism, slump, self-control); KB tagged + Drake 2013, Juliano 2004, James 2005
## [2026-10-14] endnotes | ch15 approved and saved (4 new notes: sedation, early-hours wake, REM rebound, food); KB tagged + Pietila 2018
## [2026-10-14] endnotes | ch16 approved and saved (4 new notes, protein note revised); clean copy edit 1; KB Westerterp corrected + 3 timing studies; style note recorded (lean summaries)
## [2026-10-14] endnotes | ch17 approved and saved (reserved CBT-i note written; frustration, ACT-i, screen-light notes; 2 pointers); KB tagged + Edinger 2021, Chang 2015
## [2026-10-14] endnotes | ch18 approved and saved (reserved morning-light note, outdoor brightness, light lamp; 2 pointers); clean copy edit 1
## [2026-10-14] endnotes | ch19 approved and saved (late-bedtime note; 3 pointers); clean copy 2 edits
## [2026-10-14] endnotes | ch20 approved and saved (3 new notes: training, vagus, RSA; 1 pointer); KB tagged + Rusch 2019, Berthoud DOI
## [2026-10-14] endnotes | ch21 approved and saved (1 new note)
## [2026-10-14] endnotes | ch22 approved and saved (3 new notes: post-exercise heat, morning cortisol, yoga/tai chi; 2 pointers)
## [2026-10-14] endnotes | ch23 approved and saved (reserved content-vs-light note written; negativity note; 1 pointer); clean copy edit 1
## [2026-10-14] endnotes | ch24 approved and saved (3 new notes, 1 pointer); KB cooling source corrected to Sawka 2007
## [2026-10-14] endnotes | ch25 approved and saved (ghrelin, sugar-cortisol, elimination notes; 1 pointer); KB + Malik 2008, Gonzalez-Bono 2002, Di Polito 2023, Hackett 2014
## [2026-10-14] endnotes | ch26 no claims; Phase 2 coverage COMPLETE (ch1-26). Handover written: audit/handover-phase3.md
## [2026-10-14] handover | continuation prompt written: audit/continuation-prompt-phase3.md

## [2026-10-14] verify | Ch7 Lovallo 2005 (partial tolerance confirmed; note body revised) + Leproult 1997 (sample = young men); working file + KB updated
## [2026-10-14] verify | Ch3 short-sleepers: He 2009 / Shi 2019 DOIs confirmed; 'one in a thousand' dropped (unsupported); Van Dongen 2003 added
## [2026-10-14] verify | Ch1 disease note: CDC/NINDS don't state cognitive decline; Sabia 2021 added for dementia link; note revised
## [2026-10-14] verify | Ch25 Gonzalez-Bono 2002 citation confirmed (41(3):328-333, DOI ok); sample added
## [2026-10-14] registry | link check (6 unlinked: 5 cross-refs OK; ch17 TV-lux entry given Zeitzer/Phillips); header 156->163; CLAUDE.md tagged 51->103
## [2026-10-14] endnotes | clean copy built -> audit/endnotes-clean.md (145 notes, 24 chapters; 35 pointers verified; Roenneberg fix applied); CLAUDE.md compiled count 47->145

## [2026-10-14] archive | ch01–ch26 humanizer-proposed -> /audit/archive/

## [2026-10-14] merge | all /audit/ clean copies (incl. endnotes-clean.md, 145 notes) merged into /book/ by author; CLAUDE.md note updated

## [2026-10-14] flag | ch15 "Sunday to Monday" -> "Sunday to Thursday" (author edit; confirmed in book)

## [2026-10-14] flag | ch16 "It fits where you'd expect" -> "Meal timing fits..." (author edit; confirmed in book)

## [2026-10-14] flag | ch18 "Even if only for a couple of hours" -> "Get up, and stay up for at least a couple of hours." (author edit; confirmed in book)

## [2026-10-14] flag | ch19 TV summary "for an hour" -> "for thirty minutes or more" (author edit; confirmed in book)

## [2026-10-14] flag | ch19 TV: routine line 19 -> "half an hour to an hour" (author edit; confirmed); summary "for an hour" kept

## [2026-10-14] flag | ch18 nap timing -> "Somewhere between late morning and 3pm." (author edit; confirmed; aligns with ch21 7-8h rule at 10pm bedtime)

## [2026-10-14] flag | quote punctuation: ch09 + ch26 full stops moved outside quoted phrases (Australian style); ch04 "the the" typo fixed (author edits; confirmed)

## [2026-10-14] archive | phase 2/3 working files (continuation-prompt-phase3, endnotes-coverage-working, handover-phase2-ch08, handover-phase3) -> /audit/archive/; open flags ch15/16/18/19/quotes closed

## [2026-10-14] audit | ch04 hormone simplification -> footnote 1 + Ch04 endnote now cover dopamine as well as adenosine (proposal: audit/ch04-hormone-simplification-proposed.md); KB entry retitled and updated

## [2026-10-15] sources | batch 1 (10 of 134 unique sources)
Catalogued all sources in /book/endnotes.md (134 unique: 105 STUDY, 23 REPUTABLE BODY, 6 OTHER) -> /derived/sources/catalogue.md. Saved batch 1 to /derived/sources/: cdc-2024-cdi-sleep, ninds-nd-brain-basics-sleep, sabia-2021, hill-2008, kenny-2017, kim-2007, dasilva-2025, bonnmiller-2024, saleska-2024, he-2009; index at /derived/sources/index.md. Nothing in /book/ was changed. Flags: Bonn-Miller 2024 and Saleska 2024 do not match how the Ch3 CBN/CBD note describes them (see match_notes in each file); da Silva ScienceDirect link hit a captcha (PubMed used).

## [2026-10-15] audit | ch04 hormone simplification -> clean merge copies
Full-file clean copies for diff/merge: audit/ch04-hormone-simplification-clean.md (ch04, 3 lines changed) and audit/endnotes-ch04-hormone-clean.md (endnotes, Ch4 note replaced). Source proposal: audit/ch04-hormone-simplification-proposed.md.

## [2026-10-15] sources | review log started -> /derived/sources/endnote-review-log.md (cumulative; batch 1 items 1.1-1.7 added; later batches append)

## [2026-10-15] sources | reclassified 6 sources OTHER -> REPUTABLE BODY on author's instruction (Sleep Foundation US x3, Mayo Clinic, Harvard Health, Cleveland Clinic); all now to be fetched. Counts: 105 STUDY, 29 REPUTABLE BODY, 0 OTHER. Catalogue and index updated.

## [2026-10-15] sources | batch 2 complete: 10 sources saved (sleepfoundation-nd-sleep-latency, shi-2019, cdcniosh-2020, vandongen-2003, acp-2016-qaseem, cintron-2017, reichert-2022, berridge-2007, nams-2022, roenneberg-2012). 8 full text, 2 abstract only (Van Dongen, Berridge), 0 LOW, 0 not found. Index, catalogue and endnote-review-log (items 2.1-2.7) updated.

## [2026-10-15] sources | batch 3 complete: 10 sources saved (gardiner-2024, ebrahim-2013, sleephealthfoundation-2024-melatonin, cagnacci-1997, lok-2019, hajak-1995, riemann-2002, leger-2004, lack-2023, scott-2025). 3 full text (Lok, Scott, Sleep Health Foundation), 7 abstract only (ScienceDirect bot check for Gardiner; no PMC link on PubMed for the others; publisher pages not tried), 0 LOW, 0 not found. Index, catalogue and endnote-review-log (items 3.1-3.7) updated.

## [2026-10-15] sources | batch 4 complete: 10 sources saved (lemoine-2007, wade-2010, ferracioli-oda-2013, menczel-2022, gerdin-2004, dickerson-2004, wetherell-2015, fries-2009, chan-2010, riemann-2010). 3 full text (Wade, Ferracioli-Oda, Chan & Debono), 7 abstract only (no PMC link on PubMed; publisher pages not tried), 0 LOW, 0 not found. Index, catalogue and endnote-review-log (items 4.1-4.10) updated.

## [2026-10-15] sources | batch 5 complete: 10 sources saved (lovallo-2005, leproult-1997, clark-2023, fiorillo-2003, bunzeck-2006, lack-1996, baron-2017, ohayon-2017, shaffer-2017, chinoy-2021). 4 full text (Lovallo, Baron, Shaffer, Chinoy), 6 abstract only, 0 LOW, 0 not found. Leproult found by author/journal/page because the DOI search returned nothing. Index, catalogue and endnote-review-log (items 5.1-5.10) updated.

## [2026-10-15] sources | batch 6 complete: 10 sources saved (svensson-2024, robbins-2024, schyvens-2025, kainec-2024, lindberg-1990, pardo-2021, monteleone-1992, cheah-2021, chandrasekhar-2012, langade-2019). 6 full text (Robbins, Schyvens, Kainec, Cheah, Chandrasekhar, Langade), 4 abstract only (Svensson, Lindberg, Pardo, Monteleone; no PMC link on PubMed, publisher pages not tried), 0 LOW, 0 not found. Index, catalogue and endnote-review-log (items 6.1-6.11) updated.

## [2026-10-17] sources | batch 7 complete: 10 sources saved (mah-2021, abbasi-2012, liu-2016, mason-2022, harding-2019, okamoto-mizuno-2012, sleepfoundation-2025-best-temperature, cerri-2017, haskell-1981, basner-2011). 9 full text, 1 abstract only (Haskell, not in PMC), 0 LOW, 0 not found. Sleep Foundation temperature page moved from pending to fetched in index. PMC IDs found with the PMC ID converter. Index, catalogue and endnote-review-log (items 7.1-7.10) updated.

## [2026-10-17] sources | batch 8 complete: 10 sources saved (who-2011-noise, sleephealthfoundation-2024-caffeine-and-sleep, drake-2013, juliano-2004, james-2005, agboola-2026, efsa-2015, pilcher-2015, sleephealthfoundation-2025-caffeine-food-alcohol-smoking-and-sleep, who-2023-alcohol). 7 full text, 3 abstract only (Juliano, James, EFSA), 1 LOW (WHO noise page is not the Guidelines document), 0 not found. 1 broken link (WHO alcohol news item, working copy found on who.int/azerbaijan); EFSA DOI hit a Wiley bot check, not bypassed, abstract read from the efsa.onlinelibrary page. Index, catalogue and endnote-review-log (items 8.1-8.12) updated.

## [2026-10-17] sources | batch 9 complete: 10 sources saved (pietila-2018, niaaa-nd-alcohol-metabolism, westerterp-2004, enomoto-2026, chung-2020, yan-2024, nakamura-2016, riley-2024, afaghi-2007, edinger-2021). 8 full text, 2 abstract only (Nakamura, Afaghi; no PMC link on PubMed), 0 LOW, 0 not found. 1 wrong-pages error in an endnote (Nakamura 19:30–37 vs 19(2):151-7); NIAAA page does not support its note; Riley population is prediabetes, not healthy adults. Enomoto's Measurements, Data analysis and Statistics sections sit outside the PMC "Methods" section and are included under it. Index, catalogue and endnote-review-log (items 9.1-9.10) updated.

## [2026-10-17] sources | batch 10 complete: 10 sources saved (dressle-2023, salari-2020, zeitzer-2000, phillips-2019, bauducco-2024, chang-2015, brown-2022, nccih-nd, faust-2020, lehrer-2014). 8 full text, 2 abstract only (Dressle, Bauducco), 0 LOW, 0 not found, 0 broken links. Review items 10.1-10.10 added to endnote-review-log.md (FIX: 10.3, 10.6, 10.7, 10.9). 34 sources remain.

## [2026-10-17] sources | batch 11 complete: 10 sources saved (rusch-2019, russo-2017, berthoud-2000, akimoto-2018, sleepfoundation-2026-napping, sleephealthfoundation-2024-napping, mayoclinic-2024-napping, denys-2022, leota-2025, stutz-2019). 7 full text, 3 abstract only (Berthoud, De Nys, Stutz), 0 LOW, 0 not found, 0 broken links. Review items 11.1-11.10 added to endnote-review-log.md (FIX: 11.5, 11.7). The two REPUTABLE BODY rows for Sleep Foundation and Mayo napping in index.md are now real rows. 24 sources remain.

## [2026-10-17] sources | batch 12 complete: 10 sources saved (hartstein-2024, soroka-2019, zaplatosch-2020, sawka-2007, george-1975, andersson-2018, nhsinform-nd, efsa-2010, spiegel-2004, malik-2008). 5 full text (Hartstein, Soroka, Zaplatosch, Andersson, NHS inform), 5 abstract only (Sawka, George, EFSA, Spiegel, Malik), 0 LOW, 0 not found, 0 broken links. Review items 12.1-12.10 added to endnote-review-log.md (FIX: 12.5, 12.6, 12.7). 14 sources remain.

## [2026-10-17] sources | batch 13 complete: 10 sources saved (gonzalez-bono-2002, dipolito-2023, hackett-2014, stuart-2013, sweatt-2026, verberne-2014, myszkowska-2021, minihane-2015, nhsinform-nd-food-intolerance, altinsoy-2025). 8 full text, 1 abstract only (Gonzalez-Bono), 1 NOT FOUND (NHS inform Food Intolerance: cited link is the home page only; LOW), 0 other LOW, 1 incomplete link. Review items 13.1-13.10 added to endnote-review-log.md (FIX: 13.7, 13.9, 13.10). 4 sources remain (S131-S134), including Harvard Health and Cleveland Clinic.

## [2026-10-17] sources | batch 14 complete (final): 4 sources saved (harvardhealth-nd NOT FOUND, clevelandclinic-nd, stapel-2008, aaaai-nd). 2 full text (Cleveland Clinic, AAAAI), 1 abstract only (Stapel), 1 NOT FOUND (Harvard Health; cited link is the home page only; LOW), 1 incomplete link. Review items 14.1-14.4 added to endnote-review-log.md (OPEN: 14.1). All 134 sources now collected.

## [2026-10-17] audit | endnote review log triage -> /audit/endnote-review-triage.md
Grouped Batches 1–14 of derived/sources/endnote-review-log.md into six groups plus unclassified; listed quick-win A/B decisions. No fixes applied.

## [2026-10-17] audit | endnote quick-win decisions (44 items) -> /audit/endnote-review-triage.md
Decisions recorded one at a time; follow-up list and chapter-prose flags appended. No edits to /book/ or derived/sources/.

## [2026-10-17] audit | triage groups updated with quick-win decisions -> /audit/endnote-review-triage.md
Statuses added to groups A–F; added missing items 1.1, 1.2, 8.4; new item N1 (adenosine source gap); new group G (chapter prose flags); item count corrected to 128. endnote-review-log.md not edited.

## [2026-10-17] audit | endnote Group D decisions -> /audit/endnote-review-triage.md
Warm-ups: 12.5 (George 1975 → "George CP et al."), 13.4/13.5 tags treated as OPEN, triage key adopted as the status record (log tags are hints; log not edited). Group D: 21 log items reviewed one at a time (17 DECIDED, 4 KEPT) plus the open half of 14.2 (keep "no blood test replaces it", add AAAAI). New: N2 (Ch25 background-immune note voice), FOLLOW-UP 5.5a (extra source for the Ch8 desensitise note; two UK review candidates listed), Fries 2009 to be added to the Ch7 urgency note. No new chapter flags. /book/ and derived/sources/ untouched.

## [2026-10-17] audit | endnote Group E decisions -> /audit/endnote-review-triage.md
Group E: 17 OPEN items reviewed one at a time against full text where reachable (PMC and open pages via the built-in browser; Elsevier, Wiley and Ovid pages blocked or paywalled, with second-hand checks recorded in the Decisions rows). Result: 14 DECIDED, 3 KEPT (6.6, 11.3, 12.8). New sources chosen for 8.10 (Choong 2025 meta-analysis; Yoo 2007). New FOLLOW-UPs: 6.1 (Svensson limits and funding), 10.5 (overcast daylight source), 11.2 (nasal breathing source). New chapter flags: Ch7 line 53 (5.1), Ch20 line 57 (11.2); Ch12 L-threonate 'split across the day' added to the 7.1 row (7.3). 8.7 left as FOLLOW-UP. Tally updated. No new files saved to derived/sources/; /book/ and endnote-review-log.md untouched.

## [2026-10-17] query | continuation prompt for endnote Group C pass -> /derived/continuation-prompt-endnote-group-c.md
Next pass set to Group C (11 items incl. the open half of 5.8); Group B to follow.

## [2026-10-17] audit | endnote Group C decisions -> /audit/endnote-review-triage.md
Group C: 11 items reviewed one at a time against full text where reachable (Gardiner via the Monash open copy; Dickerson & Kemeny via a university course copy; De Nys via the Stirling repository; Scott, Lok, Wade, Shaffer and Höhn on PMC via the built-in browser; Gerdin free on the FASEB site). Result: 10 DECIDED (3.2, 3.4, 3.6, 4.1 framing, 4.5, 4.6, 5.8 remainder, 7.5, 11.10, 12.1), 1 KEPT (11.8). New sources chosen: 4.6b Ch8 provocative-content note rewritten as reaction-dependent (Lerner 2007, Ottaviani 2016, Oppenheimer 2024, NINDS; Rus 2017 and Marin 2012 considered, not used); 12.1 Ch23 content-vs-light note rewritten with supporting evidence first (Höhn 2024) and balance after (Ellithorpe 2022, citation to confirm); 7.5 adds the saved Sleep Foundation temperature page. New chapter flags: Ch8 lines 23/29/61, Ch7 line 61, Ch23 line 25 (4.6b); Ch23 lines 15 and 43 (12.1). Tally updated. No new files saved to derived/sources/; /book/ and endnote-review-log.md untouched.

## [2026-10-17] audit | citation checks + Group B continuation prompt -> /audit/endnote-review-triage.md, /derived/continuation-prompt-endnote-group-b.md
6.1 Svensson FOLLOW-UP closed: ±65 min deep-sleep limits dropped (not confirmable without a paywalled or unofficial copy); 'mainly funded by Oura' kept (PubMed competing-interest record). 12.1 Ellithorpe 2022 confirmed via Crossref: *J Sleep Res* 31(5):e13551. Tally updated (FOLLOW-UP 8). Continuation prompt for the Group B pass written.

## [2026-10-17] audit | endnote Group B decisions -> /audit/endnote-review-triage.md
Group B: 13 log items plus N2 reviewed one at a time (1.4, 2.1, 2.2, 3.7 across six notes, 4.4, 8.9, 8.12 across five notes, 9.2, 10.6, 10.7, 12.6, 12.7, 13.7 with N2); all DECIDED. New sources chosen, read in full where reachable (PMC via the built-in browser, Nature, Europe PMC/Cochrane abstracts, Crossref for citations): Dijk 2009 and Phillips 2017 (Ch5 deep sleep rewritten: set by time awake, not clock time); Tordjman 2017 (melatonin peak 2–4 a.m.); Herxheimer 2002 and Liira 2014 Cochranes (melatonin uses and doses); Gooneratne 2012 (high-dose carry-over); Chang 2015 and Brown 2022 added to the evening-light note; Huberman Lab 2022 and Antonio 2024 (delayed first coffee: book's practice, Huberman's origin, expert-review balance); Cederbaum 2012 (food and alcohol absorption); Youngstedt 2019 (exercise as a clock cue); Auger 2015 and Pjrek 2020 (light-therapy lamps); Popkin 2010 (thirst). Dropped as non-supporting: Roenneberg (Ch5), NIAAA (Ch15), NCCIH (Ch18 lamp), Brown (Ch18 movement), SHF caffeine page (Ch14 coffee), CDC clause (Ch1). New item N3: Ch15 zero-alcohol note duplicated word for word (keep one). New chapter flags: Ch5 line 45, Ch6 line 77, Ch14 lines 32–34, Ch24 line 27. Tally updated (OPEN 0). Paywalls and bot-checks not bypassed (OUP, Huberman transcript). No new files saved to derived/sources/; /book/ and endnote-review-log.md untouched. Next-pass prompt: /derived/continuation-prompt-endnote-parked-rewrites.md

## [2026-10-18] query | parked-rewrites prompt updated: saving new sources to derived/sources/ now allowed (Ben); catch-up batch of ~20 earlier approved sources listed -> /derived/continuation-prompt-endnote-parked-rewrites.md

## [2026-10-18] audit | catch-up source save (20 sources) -> /derived/sources/, catalogue.md, index.md
Twenty sources approved in the Group B and C passes before the save rule was lifted now saved as S135–S154 (status APPROVED, not yet in /book/endnotes.md): Choong 2025, Yoo 2007, Lerner 2007, Ottaviani 2016, Oppenheimer 2024, Höhn 2024, Ellithorpe 2022, Dijk 2009, Phillips 2017, Tordjman 2017, Gooneratne 2012, Herxheimer 2002, Liira 2014, Antonio 2024, Huberman Lab 2022, Cederbaum 2012, Youngstedt 2019, Auger 2015 (upgraded to full text, PMC4582061), Pjrek 2020, Popkin 2010. Text from Europe PMC/PMC via the built-in browser. Yoo: metadata only (cell.com bot check, not bypassed); Choong: abstract only, Methods second-hand; Huberman Lab classed OTHER (to confirm). Points raised: Auger 'second-tier' confidence / very-low-quality evidence vs the 10.7 parenthetical 'moderate confidence'; Herxheimer Europe PMC record is the 2001 issue-1 version (Decisions cite 2002 issue 2); Liira issue (8) confirmed.

## [2026-10-18] audit | endnote parked rewrites -> /audit/endnote-review-triage.md
The three PARKED note rewrites decided one at a time, full text checked where reachable: Ch3 CBN note (1.1, 1.2, 1.3; source descriptions corrected, 'THC-type' and 'the one published human CBN trial' dropped; Lavender 2026 sleep-lab CBN trial added, S155; CLAUDE.md worked-example wording to change at housekeeping). Ch16 protein note (9.8 with 9.9; Riley dropped; Abbie 2020, Roach 2022, Morehen 2019 added, S156–S158; FLAG Ch16 line 25). Ch25 brain-fog note (13.9, 13.10; NHS inform and Altinsoy dropped; ASCIA and Lunn 2011 added, S159–S160; no flag). New review step R1 (no reinforcing negatives) added to the triage follow-up list at Ben's request, to run before the clean copy. Tally: DECIDED 99, PARKED 0. No edits to /book/ or endnote-review-log.md.

## [2026-10-18] query | continuation prompt for endnote FOLLOW-UP lookups -> /derived/continuation-prompt-endnote-followup-lookups.md

## [2026-10-18] audit | endnote follow-up lookups (part 1) -> /audit/endnote-review-triage.md
8.11 DECIDED: Anderson 2023 (*Lancet Public Health*, WHO-staff comment released as WHO/Europe's statement) replaces the dead WHO link, saved S161; first sentence of the Ch15 zero-alcohol note names WHO. N1 with 8.4/8.2 DECIDED + FLAG: Reichert 2022 (already saved) added to both Ch14 adenosine notes, wearing-off note rewritten with its closing line as the book's reasoning (R1); Ch14 line 22 flagged. 8.8/8.7 DECIDED: half-life note rewritten from the EFSA full opinion (4 h, range 2–8 h; contraceptives, some medicines, pregnancy 3–4× by term); SHF dropped; Carrillo 2000 offered, not used. Tally: DECIDED 103, FOLLOW-UP 4. No edits to /book/ or endnote-review-log.md.

## [2026-10-18] query | continuation prompt updated for the remaining FOLLOW-UP lookups -> /derived/continuation-prompt-endnote-followup-lookups.md

## [2026-10-18] audit | endnote follow-up lookups (part 2) -> /audit/endnote-review-triage.md
Remaining FOLLOW-UP lookups done, one item at a time. 11.7 DECIDED: Ch21 nap-pressure note rewritten (naps clear sleep pressure less effectively than a night's sleep; a long or late nap leaves less pressure and, after an early-evening nap, young men took longer to fall asleep); Tarokh 2021 and Werth 1996 added and saved (S162–S163), Dijk 2009 cited again, SHF kept with a scope note. 5.5a DECIDED: Ch8 reward note reframed (the evidence points to a stronger pull and more 'wanting' rather than a duller response), retitled 'Do screens recalibrate the brain's reward system?'; Wadsley & Ihssen 2023, Maza 2023 and Kuss & Griffiths 2012 added (S164–S166); no flag (Ben declined). 10.5 DECIDED: Ch18 overcast-light note 'several times brighter'; Daugaard 2019 and ILO added (S167–S168); no flag. 11.2 (nasal) DECIDED + FLAG: no study shows nose breathing slows the resting breath (Mapelli 2025: no difference at rest), so the Ch20 note now states what studies show (nose caps airflow; slower, deeper breathing in exercise); Niinimaa 1981, Eser 2024, Mapelli 2025 added (S169–S171); Ch20 line 95 flagged. Citation checks closed: Liira 2014 (8) confirmed; Herxheimer & Petrie kept as 2002 (2); Auger 2015 source line corrected (guideline gives a weak, second-tier recommendation on low to very low quality evidence; Ben kept the note summary as is). Sources saved this pass: S162–S171 (catalogue and index updated; totals 138 STUDY, 32 REPUTABLE BODY, 1 OTHER = 171). Tally: DECIDED 107, FOLLOW-UP 0, chapter flags 16 rows. No edits to /book/ or endnote-review-log.md.

## [2026-10-18] query | continuation prompt for the Group G chapter-flag review -> /derived/continuation-prompt-group-g-flag-review.md

## [2026-10-19] audit | Group G chapter-flag review -> /audit/group-g-prose-proposals.md
Ben reviewed the 16 Group G chapter-flag rows one at a time (2026-10-18 and 2026-10-19). 14 rows changed the chapter prose: Ch5 line 45 (irregular schedule, lighter hedge), Ch6 line 77 (lighter hedge; the 'rise rather than the level' mechanism has no source), Ch7 line 53 (note rewritten first, then a small hedge), Ch7 line 61 (lighter hedge), Ch8 line 23 ('the stress response'), Ch11 line 60 (Oura 'among the most studied'), Ch12 line 16 and table (PS trial dose 800 mg/day, 400 mg marked as the author's suggestion), Ch12 line 20 and table (magnesium doses from the trials), Ch13 lines 25 and 27 (18 to 20 °C), Ch14 lines 22, 32 and 34 (delayed coffee attributed to Huberman, untested; author's experience added), Ch16 line 25 (low-carb, protein-rich snack), Ch17 line 69 (lux halfway points, softened TV line), Ch23 lines 15, 41 and 43 (hedged), Ch24 line 27 (clear urine is fine). Left as written: Ch20 lines 57 and 95; Ch8 lines 29 and 61; Ch23 line 25. Note changes: Ch7 caffeine note rewritten (more in infrequent drinkers, less in daily drinkers; poor sleepers behaving like infrequent drinkers is the book's hypothesis); Ch12 magnesium note fix (144 mg per 2 g is the label figure; the 8.3% by weight calculation gives about 165 mg). New item N4 logged OPEN (steepest part of the rise, Ch6 and Ch8). Sleep-gate and melatonin-timing papers (Lavie 1997, Shochat 1997, Tzischinsky & Lavie 1994, Luboshitzky & Lavie 1998, Dollins 1994) and Borbély 1993 read as abstracts or snippets only; not saved and not cited in any note. Tally: 16 of 16 rows reviewed, N4 OPEN. No edits to /book/ or endnote-review-log.md.

## [2026-10-19] audit | N4 steepest-rise review (part 1: Ch6 lines 23–27) -> /audit/group-g-prose-proposals.md
Ben chose Option 1: line 23 names the sleep gate, a new paragraph sets out the evening stages, and one sentence on the peak is cut from line 27. New Ch6 KB note 'How does the sleep window line up with melatonin?'. Sources S172–S178 saved (Sletten 2010, Zeitzer 2007, Shochat 1997, Lavie 1997, Rajaratnam 2004, Brown 1997, Gooley 2011). Still open in N4: Ch6 27/33, Ch8 61, Ch9 50/54/56. /book/ not edited.

## [2026-10-19] audit | N4 follow-ups: wiki sleep-window timeline and KB rate-of-rise entry
Ben chose Option A for both. wiki/sleep-window.md and wiki/waking-at-2am.md: peak timing and stages updated to the N4 evidence, with the closing-window claim noted as still under review. KB entry on the rate of the melatonin rise rewritten as 'Does timing matter more than dose for melatonin?'. /book/ not edited.

## [2026-10-19] audit | cortisol-causation check (N5) -> derived/claims-knowledge-base.md, /derived/sources/, /audit/endnote-review-triage.md
Ben asked whether high cortisol is proven (or disproven) as a cause of being awake. Not proven either way. Eight sources verified on Europe PMC via its search API in the built-in browser (WebFetch rate-limited; PubMed bot check), abstracts saved as S179–S186: Dressle 2022, Vgontzas 2001 (insomnia HPA), Huscher 2009, Ismailogullari 2021, Born 1989, Friess 2004, Vgontzas 2001 (CRH, middle-aged men), Buckley 2008. New tagged Ch7 KB note 'Does high cortisol actually keep you awake?' (also cites Leproult 1997). Catalogue and index updated (totals 153 STUDY, 32 REPUTABLE BODY, 1 OTHER = 186). Vgontzas 2001 cortisol difference is P = 0.07 (ACTH significant): source line says 'borderline significance'. Pending: Ch7 loose-cortisol declaration and its note; N4 remaining lines (Ch6 27/33, Ch8 61, Ch9 54/56) to be reworded on the rumination framing. /book/ not edited.

## [2026-10-19] audit | N5 Ch7 cortisol definition -> /audit/group-g-prose-proposals.md, derived/claims-knowledge-base.md, wiki/cortisol.md
Ben approved the Ch7 line 25–27 rewrite (two speeds of the stress response; 'cortisol' = the whole slower system). Proposal filed as section 17. New tagged Ch7 KB note 'Is fight or flight cortisol or adrenaline?' (Godoy 2018, saved S187 from Europe PMC full text; Dickerson & Kemeny 2004). Wiki cortisol page: aliases and canonical updated with the definition and the literal-use rule. Totals 154 STUDY, 32 REPUTABLE BODY, 1 OTHER = 187. /book/ not edited.

## [2026-10-19] query | continuation prompt for N4 (rumination framing), knock-on fixes and the cortisol-definition sweep -> /derived/continuation-prompt-n4-rumination-cortisol-sweep.md

## [2026-10-19] audit | N4 rumination framing (part 2: Ch6 27/33, Ch8 61, Ch9 50/54/56) and knock-on fixes -> /audit/group-g-prose-proposals.md, derived/claims-knowledge-base.md, wiki/sleep-window.md
Ben approved all five rewordings (proposals sections 18–22): the pull to sleep doesn't fade after the window; lying awake lets a thought land, the mind works on it and that brings cortisol (the book's slower system) back in. Set up once in Ch6 line 27; Ch6 33, Ch8 61 and Ch9 54/56 lean on it; Ch9 50 double space only. New tagged Ch6 KB note 'Why does missing the window keep you awake?' (book's reasoning, built from rumination, clock-monitoring, hyperarousal and stimulus-control evidence; the gate stays open). Sources verified on Europe PMC (abstracts) and saved S188–S190 (Harvey 2002, Zoccola 2009, Tang 2007); cited_in added to seven saved sources. Knock-ons: wiki sleep-window canonical/body/appears_in corrected ('second wind' removed; not in /book/); KB peak note retired (merged into the sleep-window note). Totals 157 STUDY, 32 REPUTABLE BODY, 1 OTHER = 190. N4 DECIDED. /book/ not edited.

## [2026-10-19] audit | cortisol-definition sweep (N6) -> /audit/group-g-prose-proposals.md, /audit/endnote-review-triage.md
About 85 uses of 'cortisol' across 17 chapters checked against the Ch7 definition. Literal measured-hormone claims hold except four, which Ben changed: Ch7 67/79 'next morning' becomes 'next day' (section 23); Ch20 47 fight or flight now 'adrenaline up and cortisol close behind' (section 24); Ch24 9 light hedge (section 25); Ch25 39 sugar dip now 'a jolt of adrenaline … with cortisol close behind' (section 26). Ch8 23 reverted to 'Cortisol' (section 5 withdrawn). Earlier left-as-written cortisol lines (Ch8 29/61, Ch23 25) noted as covered by the definition. KB endnotes use 'cortisol' only where measured; knock-on logged for the Ch25 sugar notes (adrenaline as fast counter-regulator; source to verify). /book/ not edited.

## [2026-10-19] query | continuation prompt for the KB sync, R1, clean Notes copy and housekeeping -> /derived/continuation-prompt-kb-sync-clean-copy.md
Found that the KB (about 106 tagged entries, working headings) and /book/endnotes.md (146 notes, reader headings) have drifted: 16 headings and about 25 summaries match, and the decided rewrites were made against the Notes wording. The prompt asks Ben to confirm the sync basis first (recommended: rebuild each chapter's KB entries from Notes plus the decisions), then runs the sync chapter by chapter with per-chapter checks, R1, the clean copy and housekeeping.

## [2026-10-19] audit | KB sync, stage 4a (Ch1–Ch25) -> derived/claims-knowledge-base.md, /derived/sources/, /audit/endnote-review-triage.md
Ben chose Option A: every tagged KB entry rebuilt from its /book/endnotes.md wording plus the decided rewrites, chapter by chapter; old working headings kept as `<!-- was: … -->`. Backup: audit/archive/claims-knowledge-base-pre-sync-2026-10-19.md. 35 cross-reference notes added as tagged entries (no sources); untagged entries that were Notes notes tagged and rewritten; 9 entries merged in Notes untagged (Ch12 PS dose, Ch15 more alcohol, Ch16 carbohydrates, Ch20 vagus fibres/lungs/slow exhale, Ch22 six hours, Ch24 urine colour, Ch25 ghrelin cravings and late sugar hit); Ch7 opposition and Ch22 morning-exercise notes added (Notes-only). Retired Ch6 peak note kept out; pointers to it now target the sleep-window note. N6 knock-on: Pruessner & Meier 2026 found on Europe PMC (built-in browser), full text read, saved as S191 (totals 158 STUDY, 32 REPUTABLE BODY, 1 OTHER = 191); Ch25 evening-sugar note now says glucagon and adrenaline act first and cortisol over several hours. Statistics moved from summaries to source lines; per-chapter checks pass (URLs, no 'Sources:' label, no meta lines, cortisol literal). cited_in reconciled (16 lines added; Clark/Berridge retitled; Russo nasal line removed). KB: 148 tagged (48 contested). Decisions rows 'KB sync Ch1'–'Ch25' plus cross-reference and cited_in rows. No new N items. /book/ not edited.

## [2026-10-19] audit | R1 sweep (no reinforcing negatives) -> derived/claims-knowledge-base.md, /audit/endnote-review-triage.md
Nine follow-on 'not tested / not measured' lines removed under the standing instruction (Ch14 delayed coffee, Ch6 high dose, Ch18 movement, Ch8 novelty, Ch13 REM, Ch12 PS, Ch6 sleep window, Ch6 insomnia melatonin, Ch9 early wake); scope caveats moved to source lines where needed. Fifteen kept as direct answers to the note's question (listed in the R1 row, including the Ch18 light lamp and Ch25 sugar/cortisol candidates).

## [2026-10-19] audit | clean Notes copy -> /audit/endnotes-clean-2026-10-19.md, /audit/endnotes-clean-2026-10-19-diff.md
Compiled from the KB in Notes reading order: 148 notes, 24 chapters; 4 added (Ch6 ×2, Ch7 ×2), 2 removed (Ch6 peak, Ch15 duplicate), 1 retitled (Ch8), 97 changed in wording or sources. Ben merges by hand. /book/ not edited.

## [2026-10-19] audit | housekeeping after the KB sync -> CLAUDE.md, /audit/endnote-review-triage.md
CLAUDE.md file map: 148 tagged KB entries (48 contested), compiled 148 notes, sources S001–S191; SUMMARY PLUS SOURCES example now 'a typical dose did not change measured sleep' and points to the Ch3 note 'Is CBN really more sleep-targeted than CBD?'. Triage tally and follow-up list updated (4.7, N6 knock-on, R1, CLAUDE.md swap marked DONE). index.md unchanged (no wiki pages changed). audit/_to_delete/.addrow.py left for Ben.

## [2026-10-19] query | continuation prompt for after the KB sync (merge check, untagged stragglers) -> /derived/continuation-prompt-after-kb-sync.md

## [2026-10-19] query | continuation prompt updated: added the check of the applied chapter rewordings (Group G sections 1–26) -> /derived/continuation-prompt-after-kb-sync.md

## [2026-10-19] audit | source coverage check -> /derived/continuation-prompt-after-kb-sync.md
Every source cited in the 148 tagged notes has a saved file (Wade 2010 and Abbasi 2012 saved under their earlier links). Three sources cited only by untagged entries are unsaved (Ch10 PMC4733222 review, AASM news page, Physiopedia); added to step 3 of the continuation prompt.

## [2026-10-19] sources | format fixes in saved source files -> /derived/sources/
Ben approved fixing the format gaps found when checking the source-collection prompt against the folder (all 191 sources saved and indexed; every link in /book/endnotes.md has a saved file). 21 files changed, text as published untouched. (1) Header: removed a stray `---` line after `cited_in` in 8 files (Daugaard 2019, Eser 2024, ILO, Kuss 2012, Mapelli 2025, Maza 2023, Niinimaa 1981, Wadsley 2023), so title–access sit inside the header again. (2) Added '## Methods / Not available: abstract only.' to 13 abstract-only studies (Afaghi, Berthoud, Daugaard, Denys, George, Gonzalez-Bono, Lavie, Malik, Nakamura, Niinimaa, Spiegel, Stutz, Werth). (3) Added '## Basis' to 3 reputable-body pages: ILO and ASCIA 'No references given on the page' (ASCIA notes its Q7 'published studies' line names none); Auger 2015 'Not copied' (passage cites refs 72, 73 by number). Kept as saved: the 'Relevant text'/'Discussion' headings in 18 full-text studies, ASCIA 'Page text', Anderson 'Full text', Tarokh's own headings. Header check by script: 191/191 valid. Index and catalogue unchanged. Backups in the helper folder outside the project.

## [2026-10-19] sources | written summaries for every saved source -> /derived/sources/, index.md, CLAUDE.md
Ben asked for a summary of each source in the derived/study-summary-template.md format, from the saved text rather than the internet, added to each source file; all in one run. 191 files: a section '## Written summary (not copied text)' appended to each, with a short note that it was written from the saved text only. 188 full summaries (study template for STUDY, reputable-body template for REPUTABLE BODY; the Huberman podcast, classed OTHER, uses the reputable-body layout); 3 files with no saved text (Harvard Health, NHS inform Food Intolerance, Yoo 2007) say so instead. Details the saved text doesn't give are marked 'Not stated in the saved text'; Replication is 'Not checked (saved text only)' unless the text itself says; Evidence ratings are judgements from study type and size. Facts carried only by the source line or match_notes (e.g. Oura funding, Neurim affiliation) are labelled '(per the source line)'. Checks by script: one summary per file; copied text byte-identical to a pre-run backup; each summary's link matches the file's link field; all headlines 10 words or fewer (67 shortened); numbers in summary prose checked against the saved text (only rounding differences; Enomoto calorie figure corrected to 709–740 kcal). index.md and CLAUDE.md file map note the new section; catalogue.md and endnote-review-log.md untouched. Not touched: /book/, the KB. Points worth Ben's eye, noted in the summaries' caveats: Riley 2024 studied prediabetes (source line says healthy adults); Saleska 2024 had no placebo arm and isn't a CBN-only trial; Zaplatosch 2020's cortisol result vs its 'negligible stress' conclusion (step 4 of the continuation prompt); Lovallo 2005 gives 96 and 98 participants; WHO noise page is the 2011 fact sheet, not the 2018 guidelines.

## [2026-10-19] sources | collected the three missing source texts -> /derived/sources/ (3 files), index.md
Ben asked to collect the three sources that had no saved text. Yoo 2007: full text now saved (publisher 'Open Archive' page loaded in the built-in browser, no bot check); source-line details confirmed; link now the DOI; HIGH. Harvard Health 'Food Allergy vs. Food Intolerance': no page with that title exists; saved the closest candidate in full ('Is it a food intolerance, allergy, or something else?', 12 March 2014), LOW, other candidates listed in match_notes. NHS inform 'Food Intolerance': no such page (the likely address returns 404; archive search timed out); saved a flagged substitute from the NHS website for England ('Food intolerance', reviewed 18 June 2026), LOW, not the cited source. Each file's summary rewritten from the new text (the two candidates carry a 'not confirmed' note). index.md rows updated. Harvard and NHS inform were already dropped from the Notes, so no note changes; the Yoo text is cited only by the untagged Ch14 KB entry 'Does sleep loss reduce self-control?'. Pre-change copies kept in the helper folder outside the project.

## [2026-10-20] audit | review of the five source-summary flags -> /derived/continuation-prompt-source-flags.md
Reviewed with Ben, one at a time. Riley 2024, Saleska 2024 and WHO noise were already fixed by earlier decisions (9.8, 1.1–1.3, 8.1); the clean copy no longer carries the errors. Zaplatosch 2020: the abstract's 'negligible effect on stress' refers to salivary alpha-amylase (cortisol is classed under metabolism), so the Ch24 note is accurate; Ben chose to leave the note and the source summary as they are; step 4 of the after-KB-sync prompt closed with no change. The source summary had been corrected overnight to explain the alpha-amylase point. Lovallo 2005 (96 analysed vs 98 recruited) left for the next session. Continuation prompt written.

## [2026-10-20] audit | Lovallo 2005 participant count closed -> /derived/continuation-prompt-after-source-flags.md
Ben: 'Keep simple ignore conflict. Use 96.' Closed with no change. The abstract and Table 1 give 96 analysed (48 men, 48 women); the Methods text says 98 recruited. The Ch7 note's source line in the clean copy says '48 men and 48 women', which matches the analysed sample; no '(98 recruited)' added, and the source summary stays as written. All five source-summary flags are now closed. Checked: /book/endnotes.md (last changed 14 Oct) not yet merged; chapter files (last changed 16 Oct) do not yet carry the Group G rewordings, so steps 1 and 2 still wait on Ben. Next continuation prompt written.

## [2026-10-20] audit | Group G clean chapter copies -> /audit/group-g-clean/ (15 chapters + _diff.md)
Ben asked for full clean chapters to diff and merge instead of applying audit/group-g-prose-proposals.md by hand. Built from /book/ with sections 1–26 applied (section 5 withdrawn, not applied: Ch8 'Cortisol as the main course' kept). 37 exact-text replacements, each asserted to occur once before replacing; Ch12 quick-reference table re-padded for the two new Dosage cells. Chapters: 5, 6, 7, 8, 9, 11, 12, 13, 14, 16, 17, 20, 23, 24, 25. Check by script against the proposals file: every clean-version snippet found (the one 'miss' is section 16's line-27 text, superseded by section 18 as intended); struck wording gone. Trailing space after Ch6 line 25 'sleep window.' kept as in the book. _diff.md lists the changed lines per chapter. /book/ not touched. Noted: /book/endnotes.md changed by Ben today (02:54 UTC) but is not the clean copy (90k vs 121k chars), so step 1 still waits on the merge.

## [2026-10-20] endnote | Ch6 "Does evening light delay melatonin?" — caveat added
Added a caveat that the melatonin delay does not mean a large sleep-onset delay (Chang 2015: about ten minutes), cross-referencing the Ch17 note "How much does screen light delay sleep?". Updated derived/claims-knowledge-base.md and audit/endnotes-clean-2026-10-19.md; /book/endnotes.md unchanged, awaiting Ben's merge.

## [2026-10-20] endnote | Ch7 "Does high cortisol actually keep you awake?" — call-back to the chapter's definition of cortisol
Ben asked for the note to link back to the Ch7 rewording (Group G section 17) that describes cortisol as the last link in a chain of signals starting in the brain and defines 'cortisol' in the book as that whole slower system. CRH is now described as 'the brain signal at the start of the chain that ends in cortisol', and a closing sentence says the book uses 'cortisol' for the whole slower system, as set out earlier in the chapter. Updated derived/claims-knowledge-base.md and audit/endnotes-clean-2026-10-19.md; /book/endnotes.md unchanged, awaiting Ben's merge. The call-back depends on section 17 being applied to Ch7.

## [2026-10-21] audit | clean Notes copy -> /audit/endnotes-clean-2026-10-21.md
The 2026-10-19 clean copy was merged into /book/endnotes.md by Ben on 2026-10-20, including the Ch6 evening-light caveat and the Ch7 cortisol call-back. All 148 notes compared by script against their tagged KB entries: 147 match. One differs: the Ch23 note 'Does screen content matter more than screen light for delaying sleep?' had Brown 2022 (the Ch6 evening-light note's last source) as its fourth source, not the decided Ellithorpe 2022 (decision 12.1), which the summary's 'home study' refers to. New clean copy = /book/endnotes.md with that one line restored; only difference from the book. CLAUDE.md file map updated. /book/ not edited.

## [2026-10-21] endnote | Ch6 "Is overnight melatonin lower in people with insomnia?" — last sentence reworded
Ben's wording, tidied: 'A recent review also suggests that trouble staying asleep may go with a weaker daily rhythm, though it notes that more research is needed.' Replaces 'A recent review suggests, more tentatively, that…'. The caution is now credited to the review itself (Lack 2023 abstract: 'requires considerably more circadian research'); the Lack source line still says the evidence for the link is limited. Updated derived/claims-knowledge-base.md and audit/endnotes-clean-2026-10-21.md; /book/endnotes.md unchanged, awaiting Ben's merge.

## [2026-10-21] query | Ch6 melatonin dose evidence (0.5 mg vs higher)
- Prompted by the endnote line 'sleep comes a little sooner at the higher dose' (Ch6, 'When is taking melatonin genuinely useful?'). Herxheimer 2002 full text gives no size; the only head-to-head trial is Suhner 1998a.
- Collected S192–S196 into /derived/sources/ (Zhdanova 2001, Suhner 1998, Burgess 2010, Mundey 2005, Cruz-Sanabria 2024), status COLLECTED, pending decision. Read via web reader (PubMed, PMC and Europe PMC rate-limited or blocked mid-session), so abstract sections are close summaries, not copied text.
- Emerging picture: low dose holds for clock-shifting (Burgess, Mundey, Suhner/Herxheimer); for sleep onset and total sleep, the meta-analyses (Cruz-Sanabria 2024, Ferracioli-Oda 2013) show effects growing with dose to about 4 mg. Zhdanova 2001: 0.3 mg best for sleep efficiency in older insomniacs; no dose changed sleep latency.
- Still needed: full texts of Cruz-Sanabria 2024, Burgess 2010, Suhner 1998, Mundey 2005. No KB or /book/ changes made.
- Follow-up (same day): opened the papers in the author's Chrome. Full text read for Burgess 2010 (PMC) and Cruz-Sanabria 2024 (Wiley, free access); files updated with figures. Suhner 1998 (Taylor & Francis) and Mundey 2005 (OUP) abstracts confirmed on the publisher pages; full texts paywalled.
- Cruz-Sanabria key figures: overall 9.3 min faster onset, 19.7 min more sleep; modelled onset vs placebo about 6.6 min at 1 mg, 10.5 at 2 mg, 12.2–12.5 at 3–4 mg (derived from Table 2); timing dominates (bedtime 3.5 min, 3 h before 19.6 min); dose not significant once timing was modelled. Burgess: 0.5 mg max shift about 1.5 h, same size as 3 mg (P > 0.60), best time about 2 h later.


## [2026-10-21] endnote | Ch7 "Does high cortisol actually keep you awake?" — restructured; Dressle 2022 wording corrected
Ben asked for the note to read as 'possibly, especially if cortisol is taken as the whole chain', keeping existing wording where possible. New order: whole-chain framing and the CRH -> ACTH -> cortisol chain; CRH's stronger evidence (Vgontzas 2001 CRH: middle-aged men only); insomnia runs the chain higher (Dressle 2022; Vgontzas 2001 HPA, ACTH significant, cortisol borderline); steroid and Cushing excess; mifepristone pilot (sleep-lab measures less clear); counter-evidence (Born 1989, Friess 2004, damping CRH); reverse direction (Leproult 1997); closing line 'plausible mechanisms and some studies', firmer for the whole chain, with the call-back to the chapter. Sources unchanged. Honesty review given in chat (definition does some work; small samples; supraphysiological excess; Dressle trend). Dressle 2022: the meta-regression is a study-level, positive, non-significant trend, not 'no link'. Source line now reads 'studies with a larger cortisol difference tended to show more sleep loss, not significant' in the KB, the clean copy (audit/endnotes-clean-2026-10-21.md) and catalogue.md (2 rows) and the source file; source-file summary reworded to say studies, not people. /book/endnotes.md unchanged, awaiting Ben's merge.

## [2026-10-21] audit | Ch6 melatonin dose and timing proposals
- Collected S197–S203 via the author's Chrome (Sletten 2018 full text; Folkard 2008, Smith 2009, Lowden 2019, Micic 2016, Eastman 2005, Revell 2006 abstracts). Daugaard 2019 checked: light levels only, does not cover adaptation or light control.
- Key additions: Sletten 2018 (0.5 mg 1 h before desired bedtime, bed at that time: sleep onset about 34 min earlier in diagnosed night owls; mainly a sleep-promoting effect in the wake maintenance zone). Revell 2006 (with morning light and earlier waking, 0.5 = 3 mg, clock nearly 1 h a day). Folkard 2008 (<3% of permanent night workers fully adjust).
- Wrote audit/ch06-melatonin-dose-timing-proposals-2026-10-21.md: three prose proposals (lines 63–65, 71–73, 77; item 3 supersedes group-g item 2), five endnote proposals (one new, the 'genuinely useful' note split into jet lag / shift work / night owl, carryover note revised), KB entries to update. No /book/ or KB edits.


## [2026-10-21] query | melatonin dose and timing summary -> filed to /derived/
- Filed derived/melatonin-dose-timing-summary-2026-10-21.md: the thread's conclusions (two-force explanation, tonight vs for good, clock vs stress, dose, timing, scenarios, book changes, open items).

## [2026-10-21] query | melatonin explainer, KB entries, wiki pointers, schema line
- Moved derived/melatonin-dose-timing-summary-2026-10-21.md to derived/explainers/melatonin-dose-and-timing.md (stable living file).
- KB: three untagged entries added after 'Does a high melatonin dose carry over into the next morning?': 'Is melatonin for tonight or for good?', 'Does melatonin help more when the body clock is the problem than when stress is?', 'Why does melatonin lengthen daytime sleep after a night shift but not speed up sleep onset?'. Tagged count unchanged.
- Wiki: melatonin.md (corrected outdated supplement paragraph; two-use and clock-vs-stress pointers; notes on pending proposals); circadian-rhythm.md (two-force paragraph, pointer).
- CLAUDE.md file map: added /derived/explainers/.


## [2026-10-28] audit | Ch7 caffeine-cortisol note trim
- Ben chose the restructured last sentence of 'Does late caffeine raise cortisol?': "The book proposes that cortisol settles more slowly in people who sleep poorly, so they respond more like infrequent drinkers than daily ones."
- Applied to derived/claims-knowledge-base.md and audit/endnotes-clean-2026-10-21.md. Merge note: audit/ch07-caffeine-cortisol-note-trim-2026-10-28.md. /book/ not touched.

## [2026-10-28] audit | Ch6 melatonin proposals revised; mechanism sources
- Collected S204–S207 via the author's Chrome: Borbély 2016 (two-process model), Dijk & Czeisler 1994 (forced desynchrony), Sack 2007 AASM review (full text searched: sleep in the body's daytime shortened by the clock's alerting signal; dark goggles on commute), Åkerstedt 2003. Åkerstedt full text behind a bot check.
- Confirmed Zhdanova 2001 DOI (PMID 11600532) and Folkard 2008 citation 25(2):215–224 (PMID 18533325); fixed in sources, catalogue, KB, audit.
- Rewrote audit/ch06-melatonin-dose-timing-proposals-2026-10-21.md: new proposal 1 (line 45, clock problem vs stress problem); proposal 3 restructured around tonight vs for good (full and short versions) with clearer Sletten figures; endnotes N1–N7 (new N1 stress, new N3 mechanism, N5 shift work and N6 night owl updated).
- KB 'Why does melatonin lengthen daytime sleep…' entry: 'to source' replaced with S204–S207. Explainer and wiki circadian-rhythm.md updated. No /book/ edits; tagged count unchanged.


## [2026-10-28] audit | Ch12 magnesium L-threonate note trim
- Removed doubled cautions from the summary of 'Does magnesium L-threonate cross into the brain more effectively?' (animal studies / human RCTs; few high-quality studies / low quality; often / widely recommended; trailing 'rather than a benefit for everyone'). Grading unchanged; sources unchanged.
- Applied to derived/claims-knowledge-base.md and audit/endnotes-clean-2026-10-21.md. Merge note: audit/ch12-magnesium-threonate-note-trim-2026-10-28.md. /book/ not touched.

## [2026-10-28] audit | Ch6 melatonin: minimal-correction approach
- Author decision: keep chapter detail at its current level; correct what's there; detail stays in KB, explainer and endnotes. Author messaging checked against sources (signal not 'sedative'; 2–3 h before a usual bedtime, not 1 h; 'moving your bedtime earlier' framing for the 1 h timing; shift work 'helps a little').
- Corrected KB 'Is melatonin for tonight or for good?' and the explainer (two 'tonight' timings; moving-bedtime-earlier single plan, untested as a combination).
- Rewrote the audit file: minimal edits A (lines 63–65), B (line 73), C (line 77, decision 4.4 wording), optional D (line 45), typo; endnotes N1 (optional) to N6; mechanism note moved to KB; fuller drafts kept in an appendix as superseded. About +55 words to the chapter. No /book/ edits.

## [2026-10-28] audit | Ch6 melatonin merge-ready clean copy
- Wrote audit/ch06-melatonin-clean-copy-2026-10-28.md: full Ch6 with edits applied (lines 65, 69, 73, 77 rewording; ambiguity fixes; typos at lines 15, 27, 85–86, 88, 90). Edit D and endnote N1 dropped after the clean-copy review (clash with line 83). About +80 words. Change list at the top of the proposal file. Supersedes group-g item 2. No /book/ edits.


## [2026-10-28] audit | single clean Notes copy -> /audit/endnotes-clean-2026-10-28.md
- Ben asked for one up-to-date endnotes file to merge. Built from endnotes-clean-2026-10-21.md (which already held the 10-21 Ch6 insomnia, Ch7 cortisol, Ch23 Ellithorpe and the 10-28 Ch7 caffeine and Ch12 magnesium changes) plus the Ch6 melatonin endnote proposals N2–N6, which go with the final Ch6 clean chapter.
- KB first: tagged entries added for N2 (after slow-release), N3, N5, N4 (replacing 'When is taking melatonin genuinely useful?', retired with a comment); carryover entry first part replaced and four sources added (N6). Tagged 148 -> 151. Clean copy: 151 notes, all matched to KB by script.
- Also archived the ch07 and ch12 merge notes (folded in).
- Change list: audit/endnotes-clean-2026-10-28-changes.md (6 changed, 4 new, 1 removed vs /book/endnotes.md). Archived endnotes-clean-2026-10-21.md and the stale endnotes-ch04-hormone-clean.md to audit/archive/2026-10-28/. CLAUDE.md file map updated. Sources S192–S207 still marked COLLECTED in catalogue/index. /book/ not touched.

## [2026-10-28] decision | Ch6 melatonin endnotes N2–N6 kept in the single clean copy
- Ben confirmed the Ch6 notes stay in audit/endnotes-clean-2026-10-28.md, to merge together with audit/ch06-melatonin-clean-copy-2026-10-28.md.

## [2026-10-28] audit | Ch20 nasal breathing: second reason + endnote retitle
- Checked the case for nasal over mouth breathing in meditation. Collected S208 Watso 2023, S209 Zaccaro 2022, S210 Zelano 2016 (derived/sources/, COLLECTED; catalogue and index updated; totals 210). Lundberg nasal nitric oxide not pursued (no link to calm).
- Endnote 'Does nasal breathing naturally slow the breath?' retitled 'Is nasal breathing better for meditation?' and rewritten (airflow limit + calming effect of the nasal route); applied to the KB (old heading kept as <!-- was: -->) and audit/endnotes-clean-2026-10-28.md; change list updated (Changed 7). Tagged count unchanged (151).
- Prose proposal for Ch20 line 95: audit/ch20-nasal-breathing-proposal-2026-10-28.md (softens 'naturally slows the breath'; adds the second reason; about +55 words). Wiki meditation-and-body-scan.md notes updated. /book/ not touched.

## [2026-10-28] audit | Ch25 IgG food-sensitivity test note rewrite
- Author asked for a more positive note on IgG food-sensitivity tests; agreed wording leads with uptake and the two supportive trials, keeps the allergy-body position (ASCIA, EAACI, AAAAI) and the advice to confirm by elimination and reintroduction. Approved 2026-10-28.
- Applied to derived/claims-knowledge-base.md (now tagged contested; old heading comment kept) and audit/endnotes-clean-2026-10-28.md; change list updated (Changed 8). Tagged count unchanged (151).
- Collected S211 Atkinson 2004 (Gut, IBS RCT), S212 Alpay 2010 (Cephalalgia, migraine crossover), S213 ASCIA evidence-based vs non-evidence-based tests FAQ; source files with written summaries; catalogue (totals 213) and index updated. Wiki food-sensitivities.md notes updated. CLAUDE.md source range updated. /book/ not touched.

## [2026-11-03] query | why change is hard -> filed to /derived/explainers/
- Ben asked (chat) why, biologically, people want change but don't make the changes; then asked for the answer's claims to be sourced and filed separately from the book, as a deeper view of the willpower thread. Agreed home: a new explainer rather than the claims KB (no chapter to file under; keeps KB counts and endnote compile clean).
- New explainer derived/explainers/why-change-is-hard.md: 10 summary-plus-sources entries, a 'where this touches the book' section (Ch02, Ch14, Ch23, Ch25, Ch26), a verdict table on the original chat answer, and a reasoning-not-sourced list.
- Collected S214–S239 (26 STUDY) in derived/sources/ with written summaries; catalogue (totals 239) and index updated. Most abstract-only; Gollwitzer & Sheeran 2006 and Rise 2010 not read directly (figures from later reviews).
- Flag for a future audit (no proposal written): the 'willpower battery' image in Ch14 and Ch25 echoes ego depletion, not supported by large replications (Hagger 2016, Vohs 2021); the sourced sleep-loss → self-control claim is unaffected.
- Wiki pointers added to sleep-loss-and-self-control.md and incremental-habit-change.md. CLAUDE.md source range and explainer list updated. No KB entries; tagged count unchanged (151). /book/ not touched.

## [2026-11-04] query | why-change-is-hard explainer: cost of overriding habits
- Ben pointed out the 'costly for the brain' entry argued against a point no-one had made (extra energy) instead of explaining what the studies show. Entry rewritten as 'Why does overriding a habit feel draining?': habits run with little attention; deliberate override is costly as researchers define it, with a list of how cost is defined and measured (choice, reward given up, how it feels, what gives way under load, as a calculation, as a possible chemical cost).
- Collected S240–S247 (8 STUDY): Wood 2002, Kool 2010, Westbrook 2013, Inzlicht 2018, Otto 2013, Neal 2013, Wiehler 2022, Vadillo 2016 (willpower entry). Catalogue (totals 247), index and CLAUDE.md range updated. Raichle 2002 now cited only in the verdict table; the table row and the reasoning list reworded.
- Added a hypothesis note linking Wiehler 2022 (prefrontal glutamate after hard mental work; lead author says glutamate is cleared during sleep) to Ch14/Ch25. Not tested; no proposal written. /book/ not touched.

## [2026-11-09] query | excitement and the busy mind -> proposal + Ch8 endnote
- Ben asked (chat) about the biology of being too excited to sleep, then whether the book's cortisol/dopamine framing fits. Agreed: excitement is dopamine-driven, not a threat response; the busy mind can be driven by cortisol (urgency) or dopamine (eager).
- Proposal written: audit/ch07-ch08-excitement-busy-mind-proposed-2026-11-09.md (Ch08 'survive' → 'act'; new Ch08 excitement paragraph; Ch07 line 55 'a very common version… though not the only one'). Ch07 line refers to the Group G clean copy.
- New contested endnote 'Can looking forward to something keep you awake?' added to derived/claims-knowledge-base.md and audit/endnotes-clean-2026-10-28.md (now 152 notes); change list updated. Tagged count 152 (49 contested).
- Collected S248–S250 (Eban-Rothschild 2016, Volkow 2009, Juliff 2015) with written summaries; catalogue (totals 250) and index updated. CLAUDE.md counts and source range updated.
- Wiki dopamine.md canonical fixed (cortisol no longer described as threat response); note added. Ch07 'Outrage, excitement, genuine interest…' line left as is (author's decision). /book/ not touched.

## [2026-11-09] audit | clean copies after Group G merge
- Ben merged Group G and asked which /audit/ files still need action, with clean copies built on the current book.
- Built audit/clean-2026-11-09/: ch06 (dose/timing + typos, rebuilt on the post-Group-G chapter; old 10-28 clean copy would have undone Group G), ch07 (line 55), ch08 (line 13 + excitement paragraph), ch20 (line 95 nasal breathing), endnotes.md (152 notes), endnotes-changes.md, _diff.md, README.md. Each replacement asserted to match once.
- Moved spent or superseded files to audit/archive/2026-11-09/: group-g-prose-proposals.md, group-g-clean/, endnote-review-triage.md, endnotes-clean-2026-10-19-diff.md, ch04-hormone-simplification-proposed.md, ch06 clean copy and proposals, ch20 proposal, ch07-ch08 proposal, endnotes-clean-2026-10-28.md.
- Ch04 proposal: footnote applied by Ben (markers kept on adenosine and dopamine instead of on the '4 key hormones' line, fine). Its endnote retitle ('Are adenosine and dopamine really hormones?') was never carried into the KB; left open for Ben. CLAUDE.md paths updated. /book/ not touched.

## [2026-11-09] audit | Ch4 endnote retitle
- Ben approved the Ch4 note retitle from the archived hormone-simplification proposal: 'Is adenosine really a hormone?' → 'Are adenosine and dopamine really hormones?', with the dopamine sentence. Applied to the KB (old heading kept as a comment) and audit/clean-2026-11-09/endnotes.md; endnotes-changes.md updated (Changed 9). Note count unchanged (152). Source gap from the proposal still open: nothing in the KB yet cites dopamine's broad, hormone-like role. /book/ not touched.

## [2026-11-09] audit | endnotes: 'That … has not been shown' wording
- Ben asked to replace the formal 'That [claim] has not been shown' structure with 'It has not been directly proven that [claim]'. Scanned audit/clean-2026-11-09/endnotes.md: two instances (Ch20 vagus note, Ch25 food-sensitivity note). Both reworded in the clean endnotes and the KB; endnotes-changes.md updated (Changed 11). /book/ not touched.
- Follow-up (same day): Ben approved the same wording for the three related sentences (absorption, nasal-rhythm explanation, 'complete sequence'). Applied to the clean endnotes and the KB; endnotes-changes.md now Changed 14.

## [2026-11-09] audit | sweep misaligned/alignment (22) + build (60) -> audit/align-build-sweep-2026-11-09.md; flag: ch04 L67 one-liner reverted to "just misaligned" (Decision 1)

## [2026-11-09] audit | Ch4 note: drop 'vary across the day' for dopamine
- Searched for support. Broad-signal role: Liu, Goel & Kaeser 2021 (Nat Rev Neurosci). Daily rhythm: rats (Ferris 2014 PNAS), rodent-based review (Verwey 2016); human evidence thin/mixed (Červenka 2008; unpublished NIH poster 2016). Ben agreed to drop 'and vary across the day' from the note and keep the Ch04 footnote. Ben had already merged the clean copies, so the change is a proposal: audit/ch04-endnote-dopamine-hormone-proposed-2026-11-09.md. KB updated with Liu 2021 source line (not yet saved to derived/sources/). /book/ not touched.

## [2026-11-09] audit | sweep calming system / nervous system: rule train nervous system -> build calming system; Phase 4 heading proposal revised to "Build your calming system"; ch22 L21 compromised -> weak -> audit/align-build-sweep-2026-11-09.md
## [2026-11-09] audit | align-build clean copies: ch04 (L41, L55, L67 one-liner restored), ch20 L1 Phase 4 heading, ch22 L21 -> audit/clean-2026-11-09/; earlier merged batch notes archived
- Follow-up: saved S251 Liu 2021 to derived/sources/ with a written summary (volume/pages 22:345–358 from prior knowledge, flagged to check); catalogue (totals 251), index and CLAUDE.md range updated.
## [2026-11-11] audit | signals vs training check: compatible (signal = rep, training = consistent signals); bridge proposed ch04 L9, mapping ch10 L15, note ch20 L25 -> audit/align-build-sweep-2026-11-09.md Part 4
## [2026-11-11] audit | signals: option to retire "three signals" as framework term (keep plain-English uses); 6 lines (ch04 x5, ch10 L15) -> Part 4b

## [2026-11-11] setup | tracked changes in /book/
Book is now edited with CriticMarkup tracked changes (reviewed in Obsidian with Review Critic) instead of proposals in /audit/; applies to endnotes too. CLAUDE.md updated (new "Editing rules for /book/" section, hard rule 1). Git repo initialised in this folder (assets/Meditation ignored). CSS snippet review-critic-no-arrow added; Review Critic 2.1.1 double-click fix patched in main.js (original backed up to C:\Projects\sleep-inc).

## [2026-11-11] edit | signals -> culture/work together/three jobs: tracked changes in ch04 (L7, L9, L13, L67, L75 + new para, L79), ch10 (L13, L15), ch26 (L35). Pending review in Obsidian. Wiki updates (four-executives, sleep-incorporated-metaphor, calming-activating-systems, index) to follow after acceptance.

## [2026-11-11] edit | third job named after disruptors (matches Phase 2/5 headings): tracked changes ch10 L15, ch26 L11. Prior ch04/ch10/ch26 edits accepted and committed.

## [2026-11-11] audit | wiki sync after signals->culture edits: calming-activating-systems, sleep-incorporated-metaphor, four-executives, hormone-misalignment, index.md

## [2026-11-11] query | concept count check: two core concepts (Sleep Inc company; training/fitness) confirmed; misaligned still ~20 uses as description (ch05 L33 frames it as a problem); calming/activating system flagged as the main candidate third concept (ch10 L11-13, ch20, ch22). /book/ not touched.
## [2026-11-11] edit | ch05 L33: "alignment problem" -> "teamwork problem" (misalignment no longer framed as a problem); introduces->introduced; Its->It's. Pending review.
## [2026-11-11] edit | ch10 L13: two settings recast as what training builds (calming system + body clock), not a second diagnosis. Pending review.
## [2026-11-11] edit | retire "aligned/misalignment" as a concept -> "working together / working against each other / working as they should": 14 tracked changes (ch03 L70/76/80, ch04 L35/37/39/53/57/59/84fn, ch09 L11/15/93/95). Reverses 2026-11-09 Option C. Plain uses kept (ch02 L41, ch04 L11, ch06 L25, ch16 L31, endnotes). Pending review; wiki (hormone-misalignment, sleep-as-a-system, four-executives, index) to follow after acceptance.
## [2026-11-11] edit | ch09 L5: removed false back-reference "and said to hold it loosely" (option A). Pending review.
## [2026-11-11] audit | concept map (company / training / calming-activating) chapter by chapter, in chat. Findings: C3 named ch04 L75, pair stated ch07 L53, re-introduced ch10 L11 (settings), ch11 L46 (two modes), ch16 (activating system), ch17 L40 (sides), defined ch20 L45; no company refs ch11-15. /book/ not touched.
## [2026-11-11] derived | continuation prompt: signals + reps model -> derived/continuation-prompt-signals-reps-model.md

## [2026-11-12] derived | core model -> derived/core-model.md
- Brainstorm in chat: considered removing the company and keeping only fitness + signals; rejected (only the company does leverage, simplification, opposing forces, the shift vocabulary and the exceptions). Company kept as the single model and now carries the action: executives clocking on and off at the right times, with a clean handover between day and night shift. Signals kept as the lever (the answer to "how do I do that?": habits that send regular signals, activating or calming). Training is the change process; fitness is an illustration only. Calming system = the handover. "Trained" stays the book's word.
- Recorded the three-concepts table, the pub version (two layers), model sentence, three jobs in company terms and decision history in the new living file derived/core-model.md. CLAUDE.md file map updated.
- Marked superseded parts (inline [SUPERSEDED] notes plus a banner): wiki/sleep-as-a-system.md, wiki/sleep-incorporated-metaphor.md, derived/three-pillars-mapping.md (pillar 2 wording only), derived/continuation-prompt-signals-reps-model.md, derived/continuation-prompt-thesis-fitness.md. This reframes the 2026-09-24 fitness-as-thesis decision and partly supersedes the 2026-11-11 signals + reps model. /book/ not touched.
## [2026-11-12] derived | continuation prompt: core model rollout -> derived/continuation-prompt-core-model.md (replaces signals-reps-model prompt as the hand-off; pointer added to its banner). Also in chat: replacement analysis (fitness vs company, 17 jobs ranked by importance and fitness fit) confirmed the company stays; not filed. /book/ not touched.

## [2026-11-12] edit | ch04 core model markup
CriticMarkup added to Ch04 from the core model (derived/core-model.md): L7 culture -> set the expectations (clock on, clock off, clean handover); L11 culture -> own job and own shift; L65 last sentence cut; new good-staff paragraph before "Not broken, just not well trained."; L75 calming system = handover, CEO stops calling the wrong executives in at the wrong times; signals introduced in a new paragraph (sentences moved, not reworded). Typos at L61 and L69. Pending Ben's review. Pre-edit state was already committed at 90d29a3.

## [2026-11-12] edit | ch03 core model markup
CriticMarkup added to Ch03: fitness reduced to illustration of "not overnight". L26 illness/injury analogy cut, typo; L30 night's and question mark; L32 rewritten so the new question is answered first and fitness comes last ("A lot like getting fit."), theory/research lead-in and "over weeks" removed; L34 "Looking back at my old way of thinking"; L40 "train for it" -> several things working together, every day; L42 school list cut (L44 adults line kept). Pending Ben's review. Checkpoint commit 7cb89d5.
- Same pass: typo fixes L48, L54, L60 (x2), L64 (x2), L66.

## [2026-11-12] edit | ch10 L11-13 core model markup
Old L13 markup rejected by Ben. New CriticMarkup: activated setting -> day shift; calming system -> the handover bringing the night shift on; settings -> shifts; weak calming system -> handover that never happens; "Both can be trained" + through the signals you send every day. L15 unchanged. Checkpoint commit before pass. Pending review.

## [2026-11-12] edit | ch05 L55 typo
CriticMarkup: "Every cup is sends" -> remove "is". Signal wording kept (already consistent with the core model). Pending review.

## [2026-11-12] edit | ch11 L46 label
CriticMarkup: "activated and calm" -> "activating and calming" (book vocabulary, matches Ch20 L45). Pending review.

## [2026-11-12] edit | ch17 L40 core model
CriticMarkup: feed the activating side -> call the Wake Executives back in; calming side -> calming system gets the message through: the night shift isn't over yet (2am = holding the night, mirrors Ch07 L79). Pending review.

## [2026-11-12] edit | ch20 L25 in the moment
CriticMarkup: added ", in the moment," so L25 rejects the single in-the-moment signal, not signals. Ch16 L11, Ch20 L29-33/L45/L53/L121 checked: no change. Pending review.

## [2026-11-12] derived | continuation prompt: core model sweep -> derived/continuation-prompt-core-model-sweep.md (whole-book concept sweep against core-model.md rules; output to audit/core-model-sweep.md). Rollout decisions from this session recorded in it pending the core-model.md update.

## [2026-11-12] audit | core model sweep -> audit/core-model-sweep.md
Whole-book sweep of the core-model vocabulary (company, shifts, signals, training, fitness, retired terms) against derived/core-model.md and the 2026-11-12 rollout decisions. Read from e92af8d (rollout markup accepted). 396 chapter rows: 270 Yes, 3 No (Ch18 L45 labels, Ch16 L31 aligned, Ch02 L41 alignment), 7 Borderline, 116 Literal; 103 endnote rows, 1 Borderline (L885 follows Ch20 L51). Main pattern: label drift (side / the calm / activated state). No /book/ markup.

## [2026-11-12] edit | core model sweep fixes (CriticMarkup, pending review)
Items 1-11 from audit/core-model-sweep.md agreed with Ben in chat, 18 changes: Ch02 L41 alignment; Ch03 L38 Fix->Move; Ch04 L49 typo, L51 consultant line; Ch06 L25 align + window sentence, L29 other side; Ch16 L31 aligned; Ch17 L60 repetitions; Ch18 L45 labels; Ch20 L3 phase intro, L51 activated state / forgotten; Ch21 L15 Sleep Executives called in early (new, third job sleep side); endnotes L885 heading. Item 12 agreed: add label-drift rule and Ch21 L15 pointer to derived/core-model.md at the wiki stage. Checkpoint 7a41d5a.

## [2026-11-12] wiki | core model: thesis and metaphor pages rewritten; related pages updated
Rewrote wiki/sleep-as-a-system.md and wiki/sleep-incorporated-metaphor.md from derived/core-model.md (SUPERSEDED banners removed). Updated four-executives.md and calming-activating-systems.md (calming system = the handover; two signals; label-drift rule). Renamed hormone-misalignment.md -> working-against-each-other.md (old title kept as alias; links updated in 12 wiki pages). Removed stale align wording in cortisol.md, sleeping-pills.md, the-program.md, menopause-exception.md. Fixed YAML frontmatter (inner ": " broke parsing) in those pages, including pre-existing errors in cortisol.md and the-program.md. index.md rows updated.

## [2026-11-12] derived | core-model.md brought up to date
Marked as reflected in /book/; CEO action = setting the expectations; label-drift and in-the-moment rules added to Signals; three-jobs table updated (hold the night at 2am, Ch17 L40; sleep side Ch21 L15); open questions closed; rollout and sweep decisions added to the decision history. Still open (Ben): where the pub version and "rostering problem" hook live.

## [2026-11-12] wiki | frontmatter fix on 17 pages
Inner ": " in appears_in / canonical values broke YAML, so Obsidian could not read the properties. Replaced inner colons with " – " (14 pages) and single-quoted three values that began with a quotation (circadian-rhythm, compensatory-behaviours, incremental-habit-change). Wording unchanged. All 51 wiki pages now parse.

## [2026-11-12] derived | core-model.md: pub version placement decided
Ben: the pub version and the "rostering problem" hook are knowledge-base explanations, not book text; kept in core-model.md for later QUERY/content work. Open question closed.
