Read CLAUDE.md first and follow it exactly. /book/ is read-only; write edit proposals to /audit/, never edit the book. Do not edit endnote-review-log.md. New sources may be saved to derived/sources/ (rule lifted by Ben 2026-10-18; see 'Saving sources' below).

Context. We're working through the issues in derived/sources/endnote-review-log.md (Batches 1–14, 128 items). The working file is audit/endnote-review-triage.md (Groups A–G with a status on every item, quick wins, a Decisions table, a follow-up list with review step R1, and a tally). Finished so far: quick wins, Groups D, E, C and B, two citation checks, the catch-up save of 20 earlier-approved sources (S135–S154), the three parked note rewrites (CBN, protein, brain fog) and, in the follow-up pass (2026-10-18), 8.11 (Anderson 2023 replaces the dead WHO link; S161), N1 with 8.4/8.2 (Reichert 2022 added to both Ch14 adenosine notes; Ch14 line 22 flagged) and 8.8/8.7 (half-life note rewritten from the EFSA full opinion). Tally: DECIDED 103, FOLLOW-UP 4, PARKED 0. Read the triage file in full before starting.

Status labels: the triage key (DECIDED / KEPT / FOLLOW-UP / PARKED / OPEN, + FLAG) is the record. The log's own tags are the collector's first impressions only.

This pass: the remaining FOLLOW-UP lookups, one item at a time, in this order:
1. 11.7 Ch21 'Do naps use up the sleep pressure you need for the night?': find, save and check Tarokh et al. 2021 (naps vs night sleep dissipating sleep pressure) as the mechanism source; the note currently cites only the SHF Napping page, which does not support the mechanism. Dijk 2009 (saved, S142: an early-evening nap reduced deep sleep that night) may also help.
2. 5.5a Ch8 desensitise note: decide on the two candidates already found (Kuss & Griffiths 2012; Kuss, Pontes & Griffiths 2018; see the follow-up list for caveats) or search again.
3. 10.5 Ch18 'even under cloud': a source for overcast daylight levels (Ch18 line 19 relies on it).
4. 11.2 Ch20 nasal breathing slowing the breath: find a source (Ch20 line 95 relies on it).
5. Citation checks before the clean copy: 3.7c Liira 2014 issue number — Europe PMC shows (8), 2014 Aug (found in the catch-up save; record it and close). Herxheimer & Petrie: Europe PMC holds the 2001 issue-1 version; confirm whether to cite 2002 (2) or 2001 (1). 10.7 Auger 2015 parenthetical: the guideline says 'second-tier degree of confidence' and rates the ASWPD light-therapy evidence VERY LOW (saved file S152); decide whether 'with moderate confidence' should change.
Leave anything not on this list unless I ask.

Also open from the catch-up save (only if I ask): Yoo 2007 has no saved text (cell.com bot check); Choong 2025 Methods are second-hand only (LJMU repository PDF); Huberman Lab classed OTHER (confirm or reclass).

How to run it:
- The project folder is connected; work in it with device_bash ($HOME/mnt/Sleep Incorporated). If it isn't, request access to C:\Users\bencm\OneDrive\Documents\Claude\Brain\Sleep Incorporated with device_request_folder_access.
- One item at a time, using AskUserQuestion. Where a lookup changes a note's wording, show the full proposed note text (summary and source lines) in the option description or, if long, in a SendUserMessage first.
- Before each question, read the log entries, the current note text in book/endnotes.md, the matching source files in derived/sources/ and the earlier Decisions rows. Don't rely on memory. Quote the note's actual current wording.
- Full text: check each source file's `access` field. If ABSTRACT ONLY, try to read the full text before asking, and say plainly what you checked and what you found.
  - What worked: open-access PDFs fetched inside the publisher tab and read with pdf.js from cdnjs (worked for the EFSA Journal opinion on efsa.onlinelibrary.wiley.com via /doi/pdfdirect/…; only for open-access items); PMC via the built-in browser (mcp__remote-devices__Claude_Browser__*: open one tab with preview_start, navigate it, pull text with javascript_tool on document.body.innerText or section p elements); Europe PMC REST API (www.ebi.ac.uk/europepmc/webservices/rest/search, /<PMCID>/fullTextXML and /MED/<PMID>/references, fetched from inside a tab on ebi.ac.uk) for abstracts, open-access status, full text and reference lists; the Crossref API (api.crossref.org/works/<doi>) for citation details; APA PsycNet full text when Europe PMC lists an Unpaywall open copy; open university repositories; Nature/PLOS/Frontiers/FASEB pages; Cochrane abstracts via Europe PMC; professional-body pages (e.g. ASCIA).
  - The computer's shell has no internet; text reaches files only by transcription, so copy carefully and keep saved Methods to the relevant paragraphs, saying so in match_notes.
  - Do not get round bot-checks or paywalls (ScienceDirect, cell.com, OUP 'Just a moment', Ovid, Wiley, Springer, the Huberman Lab Premium transcript), and don't use unofficial uploads. If blocked, try an open repository copy or a reputable second-hand report and say it is second-hand.
  - If full text can't be reached, say so and include a "mark FOLLOW-UP" option.
  - Record what the full text showed in the Decisions row as well.
- Explanation length: what the note says, what the sources say, and why it matters (two to three times a one-line table entry).
- Give 2–3 options, recommended first, with short descriptions.
- Check whether the chapter prose (book/chNN - *.md) relies on the point. If a note change would put it out of step with the chapter, offer to flag the prose (Group G) as its own question, with the line number. Also check other chapters for the same claim.
- If I ask a clarifying question instead of choosing, answer it plainly (SendUserMessage if it needs more than a line), then re-ask. If I ask to pause, stop and wait.
- If I ask for a better source, search (systematic reviews or meta-analyses from developed Western countries first), read it, and offer it.
- Saving sources: when I approve a decision that uses a new source, save it to derived/sources/ in the same format as batches 1–14 (frontmatter: source_type, source_line, cited_in, title, authors_or_body, year, journal_or_publisher, link, link_checked, match_confidence, match_notes, access; then Abstract / Methods / Relevant text / Page text as fits), named author-year-short-title.md. Add it to derived/sources/catalogue.md (next ID after S161, status APPROVED; update the totals line) and derived/sources/index.md (update the count line). Only sources I approve; don't save rejected candidates. Don't edit existing source files other than adding a note to `cited_in` when an already-saved source is newly cited.
- After each decision, add a row to the Decisions table (insert before "### Follow-up list from this round", keeping the blank line before the heading) with a short in-place Python edit (python3 -I with a heredoc; don't write helper scripts into the project folders). Update the item's status in its group table (FOLLOW-UP → DECIDED). Add new issues as N-numbered items (N1–N3 exist; next is N4), chapter flags to Group G and the flag list, new follow-ups to the follow-up list. Keep the tally current.
- At the end, append a log.md entry, e.g. ## [date] audit | endnote follow-up lookups -> /audit/endnote-review-triage.md, and write the next continuation prompt (Ben's review of the Group G chapter flags) to derived/.

Preferences already set (apply them, don't re-ask):
- Citations keep the volume:pages style; long author lists use "First AB et al."
- Web pages stay undated, except the Sleep Foundation nap page.
- Prefer sources from developed Western countries.
- When the evidence creates tension with the chapter, put the most factual version in the Notes and offer to flag the chapter prose rather than bending the note. (I often decline a flag when the prose is already hedged; offer it, don't assume it.)
- When a statement is the book's own advice or reasoning, frame it that way rather than attributing it to a source. End such a line at "…is the book's reasoning/suggestion": don't add "it has not been tested" on top. Where the note answers a factual question directly, state plainly what has or hasn't been shown.
- No reinforcing negatives (review step R1): where a note already says the research is thin, or frames the point as the book's recommendation or another non-research basis, don't follow it with a confirming line that nothing specific has been studied. Apply this to any wording written in this pass.
- A popular-science origin (e.g. Huberman) can be cited as the origin of advice, with the balance evidence after it.
- The author's personal experience belongs in the chapter, not the encyclopedia-voice note: carry such requests into a Group G flag.
- House style is summary plus sources: neutral encyclopedia voice, no statistics language in the summary prose (figures go in the source-line parenthetical). Remove meta lines that talk about "the book's framing" or "the claim is directionally correct" when a note is touched.
- Scope caveats (sample size, single study, population, extrapolation) usually go in the source-line parenthetical rather than the summary.
- Don't add summary sentences that undercut our own sources just because they weren't tested in exactly the book's scenario; keep that kind of scope note in the parenthetical.
- When a note mixes supporting and balancing evidence, put the supporting studies first (summary and source list), then the balance.
- When people respond differently, say so.
- Quantify comparisons where a source allows (e.g. 0.5 vs 5 mg melatonin), in the parenthetical.
- Second-hand confirmation is acceptable when full text is blocked, provided the Decisions row says so.
- Credibility caveats (industry sponsor, contract research company) go in the source-line parenthetical.

Don't: fix anything in /book/.

Housekeeping: audit/_to_delete/.addrow.py is a stray helper from the Group E pass; leave it for me to delete.

After the FOLLOW-UP lookups, the remaining stages are: my review of the Group G chapter flags → apply all decisions to derived/claims-knowledge-base.md → R1 sweep (no reinforcing negatives) across all decided note wording → compile a clean Notes copy in /audit/ (check cross-references, headings, citation style, and drop the N3 duplicate) → housekeeping (update CLAUDE.md counts; CLAUDE.md SUMMARY PLUS SOURCES example swap 'benefit came mainly from THC-type compounds' → 'a typical dose did not change measured sleep' and replace the 'Ch03.1 (CBN)' pointer with the Ch3 note heading; delete the stray helper).
