Read CLAUDE.md first and follow it exactly. /book/ is read-only; write edit proposals to /audit/, never edit the book. Do not edit endnote-review-log.md. New sources may now be saved to derived/sources/ (rule lifted by Ben 2026-10-18; see 'Saving sources' below).

Context. We're working through the issues in derived/sources/endnote-review-log.md (Batches 1–14, 128 items). The working file is audit/endnote-review-triage.md. It has Groups A–G with a status on every item, a quick-wins section, a Decisions table, a follow-up list and a tally. Finished so far: the quick-win pass, the Group D, E, C and B passes, and two citation checks. After the Group B pass (2026-10-17) no log items are OPEN; N2 and N3 are DECIDED. Read the triage file in full before starting.

Status labels: the triage key (DECIDED / KEPT / FOLLOW-UP / PARKED / OPEN, + FLAG) is the record. The log's own tags are the collector's first impressions only.

This pass: the three PARKED note rewrites, one note at a time, in this order:
1. Ch3 CBN note, 'Is CBN really more sleep-targeted than CBD?' (log 1.1, 1.2, 1.3; Decisions rows 1.1/1.2/1.3 and 1.3a). Bonn-Miller 2024 is a CBN trial (fewer awakenings; CBD added nothing) and Saleska 2024 compared CBD with CBD+CBN (no difference): their descriptions are currently swapped. Drop 'the one published human CBN trial'. Settle the da Silva 2025 wording ('THC-type compounds' vs the abstract's 'non-CBD cannabinoids'). CLAUDE.md names this note (Ch03.1 in the KB) as the worked example for SUMMARY PLUS SOURCES; if the rewrite changes it, propose the CLAUDE.md wording change as well.
2. Ch16 protein note, 'Does protein steady overnight blood sugar?' (log 9.8, 9.9; Decisions rows 9.8 and 9.9). Riley 2024 doesn't test protein, and its parenthetical is wrong (adults with prediabetes; fasting glucose). Carry in the 9.9 decision: keep 'by raising insulin'; Afaghi parenthetical '(small study of 12 healthy men; high-glycaemic meal four hours before bed)'. Likely needs a new source on a protein (or mixed) evening snack and overnight glucose.
3. Ch25 brain-fog note, 'Can food sensitivity cause disrupted sleep and brain fog?' (log 13.9, 13.10; Decisions row 13.9/13.10 brain fog). The NHS inform page was not found (home page only) and Altinsoy & Dikmen 2025 excluded food intolerance. Also check the nasal-congestion clause. Keep in step with the 13.7 decision (same chapter: background immune response 'has not been shown'; IgG4 tests don't identify foods) and the triggers note (Cleveland Clinic + AAAAI).

Leave the FOLLOW-UP lookups (8.11, 8.8/8.7, 11.7, N1, 5.5a, 10.5, 11.2, 3.7c Liira issue number) unless I ask. Where a rewrite overlaps one, say so and decide only the rewrite.

How to run it:
- The project folder is connected; work in it with device_bash ($HOME/mnt/Sleep Incorporated). If it isn't, request access to C:\Users\bencm\OneDrive\Documents\Claude\Brain\Sleep Incorporated with device_request_folder_access.
- One note at a time, using AskUserQuestion. For a whole-note rewrite, show the full proposed note text (summary and source lines) in the option description or, if long, in a SendUserMessage first.
- Before each question, read the log entries, the current note text in book/endnotes.md, the matching source files in derived/sources/ and the earlier Decisions rows. Don't rely on memory. Quote the note's actual current wording.
- Full text: check each source file's `access` field. If ABSTRACT ONLY, try to read the full text before asking, and say plainly what you checked and what you found.
  - What worked: PMC via the built-in browser (mcp__remote-devices__Claude_Browser__*: open one tab with preview_start, navigate it, pull text with javascript_tool on document.body.innerText with a regex for the key terms); Europe PMC REST API (www.ebi.ac.uk/europepmc/webservices/rest/search, fetched from inside the browser tab) for abstracts and open-access status; the Crossref API (api.crossref.org/works/<doi>) for citation details; open university repositories; Nature/PLOS/Frontiers/FASEB pages; Cochrane abstracts via Europe PMC.
  - Do not get round bot-checks or paywalls (ScienceDirect, OUP 'Just a moment', Ovid, Wiley, Springer, the Huberman Lab Premium transcript), and don't use unofficial uploads. If blocked, try an open repository copy or a reputable second-hand report and say it is second-hand.
  - If full text can't be reached, say so and include a "mark FOLLOW-UP" option.
  - Record what the full text showed in the Decisions row as well.
- Explanation length: what the note says, what the sources say, and why it matters (two to three times a one-line table entry).
- Give 2–3 options, recommended first, with short descriptions.
- Check whether the chapter prose (book/chNN - *.md) relies on the point. If a note change would put it out of step with the chapter, offer to flag the prose (Group G) as its own question, with the line number. Also check other chapters for the same claim.
- If I ask a clarifying question instead of choosing, answer it plainly (SendUserMessage if it needs more than a line), then re-ask. If I ask to pause, stop and wait.
- If I ask for a better source, search (systematic reviews or meta-analyses from developed Western countries first), read it, and offer it.
- Saving sources (approved 2026-10-18): when I approve a decision that uses a new source, save it to derived/sources/ in the same format as batches 1–14 (frontmatter: source_type, source_line, cited_in, title, authors_or_body, year, journal_or_publisher, link, link_checked, match_confidence, match_notes, access; then Relevant text / Abstract, Methods, Basis as fits), named author-year-short-title.md. Add it to derived/sources/catalogue.md (next ID after S134, status APPROVED) and derived/sources/index.md. Only sources I approve; don't save rejected candidates. Don't edit existing source files other than adding a note to `cited_in` when an already-saved source is newly cited.
- After each decision, add a row to the Decisions table (insert before "### Follow-up list from this round") with a short in-place Python edit (don't write helper scripts into the project folders). Update the item's status in the Group B table (PARKED → DECIDED) and in Group C for 1.3 (THC-type). Add new issues as N-numbered items (N1–N3 exist; next is N4), chapter flags to Group G, new follow-ups to the follow-up list. Keep the tally current.
- At the end, append a log.md entry, e.g. ## [date] audit | endnote parked rewrites -> /audit/endnote-review-triage.md, and write the next continuation prompt (FOLLOW-UP lookups) to derived/.

Preferences already set (apply them, don't re-ask):
- Citations keep the volume:pages style; long author lists use "First AB et al."
- Web pages stay undated, except the Sleep Foundation nap page.
- Prefer sources from developed Western countries.
- When the evidence creates tension with the chapter, put the most factual version in the Notes and offer to flag the chapter prose rather than bending the note. (I often decline a flag when the prose is already hedged; offer it, don't assume it.)
- When a statement is the book's own advice or reasoning, frame it that way rather than attributing it to a source. End such a line at "…is the book's reasoning/suggestion": don't add "it has not been tested" on top (no need to keep reinforcing the negative). Where the note answers a factual question directly, state plainly what has or hasn't been shown.
- A popular-science origin (e.g. Huberman) can be cited as the origin of advice, with the balance evidence after it.
- The author's personal experience belongs in the chapter, not the encyclopedia-voice note: carry such requests into a Group G flag.
- House style is summary plus sources: neutral encyclopedia voice, no statistics language in the summary prose (figures go in the source-line parenthetical). Remove meta lines that talk about "the book's framing" or "the claim is directionally correct" when a note is touched.
- Scope caveats (sample size, single study, population, extrapolation) usually go in the source-line parenthetical rather than the summary.
- Don't add summary sentences that undercut our own sources just because they weren't tested in exactly the book's scenario; keep that kind of scope note in the parenthetical.
- When a note mixes supporting and balancing evidence, put the supporting studies first (summary and source list), then the balance.
- When people respond differently, say so.
- Quantify comparisons where a source allows (e.g. 0.5 vs 5 mg melatonin), in the parenthetical.
- Second-hand confirmation is acceptable when full text is blocked, provided the Decisions row says so.

Don't: fix anything in /book/. Don't do the FOLLOW-UP lookups in this pass unless I ask.

Housekeeping: audit/_to_delete/.addrow.py is a stray helper from the Group E pass; leave it for me to delete.

After the parked rewrites, the remaining stages are: FOLLOW-UP lookups → my review of the Group G chapter flags → apply all decisions to derived/claims-knowledge-base.md → compile a clean Notes copy in /audit/ (check cross-references, headings, citation style, and drop the N3 duplicate) → housekeeping (update CLAUDE.md counts, delete the stray helper).

Catch-up still owed: about 20 sources approved before the rule was lifted have no saved file (Group C: Choong 2025, Yoo 2007, Lerner 2007, Ottaviani 2016, Oppenheimer 2024, Höhn 2024, Ellithorpe 2022; Group B: Dijk 2009, Phillips 2017, Tordjman 2017, Gooneratne 2012, Herxheimer 2002, Liira 2014, Antonio 2024, Huberman Lab 2022, Cederbaum 2012, Youngstedt 2019, Auger 2015, Pjrek 2020, Popkin 2010). Collect them as one batch when I ask, at the latest before the knowledge-base step (links are in the Decisions rows; Auger 2015 is on PMC as PMC4582061, so upgrade it to full text).
