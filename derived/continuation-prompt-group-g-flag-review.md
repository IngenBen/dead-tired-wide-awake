Read CLAUDE.md first and follow it exactly. /book/ is read-only; write edit proposals to /audit/, never edit the book. Do not edit derived/sources/endnote-review-log.md. Existing source files in derived/sources/ are not edited (except adding a note to `cited_in` when an already-saved source is newly cited).

Context. We are working through the issues in derived/sources/endnote-review-log.md (Batches 1-14, 128 items). The working file is audit/endnote-review-triage.md (Groups A-G with a status on every item, a Decisions table, a follow-up list, review step R1 and a tally). Finished: quick wins, Groups D, E, C and B, the parked note rewrites, the catch-up source save, and (2026-10-18) every FOLLOW-UP lookup and the three citation checks: 8.11, N1 with 8.4/8.2, 8.8/8.7, 11.7 (Ch21 nap note; Tarokh 2021 + Werth 1996), 5.5a (Ch8 reward note reframed to a stronger pull and retitled "Do screens recalibrate the brain's reward system?"; Wadsley 2023, Maza 2023, Kuss 2012), 10.5 (Ch18 overcast note; Daugaard 2019 + ILO), 11.2 nasal (Ch20 note rewritten; Niinimaa 1981, Eser 2024, Mapelli 2025), Liira (8) confirmed, Herxheimer & Petrie kept as 2002 (2), Auger 2015 source line corrected. Tally: DECIDED 107, KEPT 33, FOLLOW-UP 0, PARKED 0, OPEN 0. Sources saved: S001-S171 (derived/sources/catalogue.md and index.md). Read the triage file in full before starting (use Read with offset/limit, or several device_bash calls; it is about 110 KB).

This pass: Ben's review of the Group G chapter flags (16 rows in Group G of the triage file). These are comments on Ben's own chapter prose, so ask about every flag; the standing instruction below (take the recommended option unless it weakens the claim) applies to note wording, not to the author's prose. Work through the flags one at a time, grouped by chapter so each chapter file is read once, in this order:

- Ch5: 2.1, line 45 (irregular schedule and deep sleep)
- Ch6: 4.4, line 77 (high dose "responds to the rise rather than the level"; needs a source)
- Ch7: 5.1, line 53 (evening baseline cortisol after caffeine); 4.6b, line 61 (baseline cortisol creeps up)
- Ch8: 4.6b, lines 23, 29 and 61 (cortisol wording)
- Ch11: 6.3, about line 60 (Oura "most published research")
- Ch12: 6.7 (phosphatidylserine dose); 7.1 and 7.3 (evening magnesium dose; line 20 "studies often split it across the day")
- Ch13: 7.9 ("16 to 20 degrees Celsius (roughly 60 to 68 Fahrenheit)")
- Ch14: 8.9, lines 32-34 (delayed first coffee; Ben wants his own experience added); N1, line 22 (afternoon slump)
- Ch16: 9.8, line 25 (protein and overnight blood sugar)
- Ch17: 10.3, about lines 69-71 (25 lux and the TV)
- Ch20: 11.2, line 57 (exhale "mechanically activates the vagus nerve") and 11.2 nasal, line 95 (nasal breathing "naturally slows the breath")
- Ch23: 12.1, lines 15 and 43 (screen content vs light); 4.6b, line 25 (cortisol from things that provoke you)
- Ch24: 12.7, line 27 ("Clear means you've overdone it")

How to run it:
- The project folder is connected; work in it with device_bash ($HOME/mnt/Sleep Incorporated). If it isn't, request access to C:\Users\bencm\OneDrive\Documents\Claude\Brain\Sleep Incorporated with device_request_folder_access.
- Before each question, read the actual chapter lines in book/chNN - *.md (quote the current wording, with the previous and following paragraph), the Group G row and the Decisions row it came from, and the current note wording in book/endnotes.md. Do not rely on memory. Also check other chapters for the same claim.
- One flag per AskUserQuestion. Options (2-3, recommended first): (1) a proposed rewording that fits the evidence and keeps Ben's voice; (2) a lighter hedge; (3) leave as written. Show the proposed rewording in chat using the REWORD display rules from CLAUDE.md: plain rendered text (not a code block), **bold** for added wording, ~~strikethrough~~ for removed wording, previous paragraph + amended paragraph + following paragraph (add one more paragraph on a side whose neighbour is 2 sentences or fewer). Use SendUserMessage for the rewording, then ask. Where Ben wants his own experience added (8.9), draft it in his voice from author-style-notes.md and keep it clearly personal (for example "I felt..., though that could be placebo"). When a flag needs a source, say so plainly.
- If Ben asks a clarifying question instead of choosing, answer it plainly, then re-ask. If he asks to pause, stop and wait. If he asks for a better source, search (systematic reviews or meta-analyses from developed Western countries first), read it, and offer it.
- Record every decision: add a row to the Decisions table in the triage file (insert before "### Follow-up list from this round", keeping the blank line before the heading) with a short in-place Python edit (python3 -I with a heredoc; no helper scripts in the project folders). Mark the Group G row as reviewed (date and decision) by adding it to the row's text. Keep the tally current. Add new issues as N-numbered items (N1-N3 exist; next is N4).
- Approved rewordings go to audit/group-g-prose-proposals.md (create it on the first approval, then append): for each, chapter file, line number, the full current paragraph, the full proposed paragraph (additions in bold, removals struck through), the reason, and the supporting source or note it matches. Never write to /book/. Declined flags are recorded in the Decisions table only.
- If a decision changes a note's wording (for example the note should now match the revised prose), apply the standing instruction below and record it in the same Decisions row.
- At the end, append a log.md entry, for example ## [date] audit | Group G chapter-flag review -> /audit/group-g-prose-proposals.md, and write the next continuation prompt (apply all decisions to the knowledge base, then the R1 sweep) to derived/.

Standing instruction (Ben, 2026-10-18): for note wording, take the recommended option without asking unless the change would weaken the claim in the note; ask only then, and continue to the next item. (Ben's dictated sentence was unclear after "then"; this reading was applied during the follow-up pass: ask only when the change weakens the claim.)

Preferences already set (apply them, don't re-ask):
- Citations keep the volume:pages style; long author lists use "First AB et al."
- Web pages stay undated, except the Sleep Foundation nap page.
- Prefer sources from developed Western countries.
- When the evidence creates tension with the chapter, put the most factual version in the Notes and offer to flag the chapter prose rather than bending the note. (Ben often declines a flag when the prose is already hedged; offer it, don't assume it.)
- When a statement is the book's own advice or reasoning, frame it that way rather than attributing it to a source. End such a line at "...is the book's reasoning/suggestion": don't add "it has not been tested" on top. Where the note answers a factual question directly, state plainly what has or hasn't been shown.
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

Don't: fix anything in /book/. Don't re-open decided note wording unless Ben asks or a prose decision makes the note inconsistent.

Housekeeping: audit/_to_delete/.addrow.py is a stray helper from the Group E pass; leave it for Ben to delete.

After this pass, the remaining stages are: apply all decisions to derived/claims-knowledge-base.md (including the Ch8 heading change "Do screens recalibrate the brain's reward system?", the Russo cited_in line for the nasal note, and the Auger source line) -> R1 sweep (no reinforcing negatives) across all decided note wording; candidates already spotted: 8.9 Ch14 delayed-coffee note, 4.5 Ch6 high-dose note, 10.6 Ch18 morning-movement note, 10.7 Ch18 light-lamp note ("though no study has compared them directly..."), 13.1-13.3 Ch25 sugar/cortisol closing line; check also the new Ch20 nasal note and the Ch8 reward note -> compile a clean Notes copy in /audit/ (check cross-references, headings, citation style, and drop the N3 duplicate) -> housekeeping (update CLAUDE.md counts; CLAUDE.md SUMMARY PLUS SOURCES example swap 'benefit came mainly from THC-type compounds' -> 'a typical dose did not change measured sleep' and replace the 'Ch03.1 (CBN)' pointer with the Ch3 note heading; delete the stray helper; tidy the stale links and notes in the saved files S146 (links to the 2001 version) and S152 (old Auger wording) only if Ben asks).

Also open (only if Ben asks): Yoo 2007 has no saved text (cell.com bot check); Choong 2025 Methods are second-hand only (LJMU repository PDF); Huberman Lab classed OTHER (confirm or reclass).
