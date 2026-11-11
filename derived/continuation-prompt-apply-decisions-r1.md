Read CLAUDE.md first and follow it exactly. /book/ is read-only; write edit proposals to /audit/, never edit the book. Do not edit derived/sources/endnote-review-log.md. New sources may be saved to derived/sources/ (rule lifted by Ben 2026-10-18).

Context. We have been working through derived/sources/endnote-review-log.md (Batches 1-14, 128 items). The working file is audit/endnote-review-triage.md (Groups A-G, Decisions table, follow-up list with review step R1, tally). Finished: quick wins, Groups D, E, C and B, the parked note rewrites, the catch-up source save, the follow-up lookups, and (2026-10-18 and 2026-10-19) the Group G chapter-flag review: all 16 rows reviewed, 14 changed the chapter prose, 2 left as written. The approved chapter rewordings are in audit/group-g-prose-proposals.md (15 sections). Ben applies those to the chapters by hand, so do not apply them yourself. Read the triage file in full before starting.

This pass: apply all DECIDED note wording to the knowledge base, then run review step R1.

Part 1 - apply decisions to derived/claims-knowledge-base.md (the working file). Use the Decisions table in the triage file as the record, in order, and apply every row that changes a note (summary text, source lines, new sources with cited_in, retitled headings). Two rows from the Group G pass need particular care:
- 5.1 (Ch7 note, revised at Flag 3): Ch7 'Does late caffeine raise cortisol?' summary now says caffeine raises cortisol more in people who rarely drink it than in daily drinkers, and that poor sleepers returning to baseline more slowly and behaving like infrequent drinkers is the book's hypothesis. It replaces the earlier 5.1 summary wording.
- 7.3 (note fix, found at Flag 8): Ch12 magnesium note. The decided parenthetical '(about 8.3% by weight, worked out from the compound's molecular weight)' does not match 144 mg per 2 g (8.3% of 2 g is about 165 mg; 144 mg is the product-label figure for a 2,000 mg Magtein serving). Use 'a 2 g (2,000 mg) compound serving delivers about 144 mg of elemental magnesium, as printed on product labels' and add '(product label figure)' to the source line.
Keep the house style in CLAUDE.md and author-style-notes.md. Report which rows were applied and any row that could not be applied cleanly, and ask me about those one at a time.

Part 2 - review step R1 (no reinforcing negatives) across the notes. Known candidates from the Group G pass, where the chapter was left as written or the note still carries the wording:
- Ch7 pointer note 'Does constant stimulation keep cortisol higher?' ('has not been directly measured').
- Ch8 lines 29 and 61 and Ch23 line 25 (the chapter still says cortisol for the outrage jolt; the Ch8 note does not support cortisol as the mechanism).
- Ch20 lines 57 and 95 (vagus 'mechanically activates'; nasal breathing 'naturally slows the breath'), left as written.
These are chapter-prose items: list them for Ben, do not rewrite them.

Part 3 - new item N4 (Ch6 lines 23, 25, 33; Ch8 line 61: 'melatonin rising steeply', 'the steepest part of the rise'). Status OPEN. Sleep-gate research (Lavie 1997 review; Shochat, Luboshitzky and Lavie 1997; Rajaratnam 2004) ties the abrupt rise in sleep propensity to the onset of the evening melatonin rise, not specifically its steepest part, and as an association. Only if I ask: read the Ch6 and Ch8 lines, show the current wording, and offer rewordings one flag at a time (same format as the Group G review: previous paragraph, amended paragraph with strikethrough and bold, following paragraph; Option 1 recommended, Option 2 lighter hedge, Option 3 leave). Sources read as abstracts only and not saved: Borbely 1993, Lavie 1997, Shochat 1997, Tzischinsky and Lavie 1994, Luboshitzky and Lavie 1998, Dollins 1994. Save them to derived/sources/ only if a note cites them.

Also open (only if I ask): Yoo 2007 has no saved text (cell.com bot check); Choong 2025 Methods are second-hand only; Huberman Lab is classed OTHER (confirm or reclass).

How to run it:
- The project folder is connected; work in it with device_bash ($HOME/mnt/Sleep Incorporated). If it is not, request access to C:\Users\bencm\OneDrive\Documents\Claude\Brain\Sleep Incorporated with device_request_folder_access.
- Record every decision as a row in the Decisions table (insert before '### Follow-up list from this round', keeping the blank line before the heading) with a short in-place Python edit (python3 -I with a heredoc; no helper scripts in the project folders). Keep the tally current.
- Standing instruction (Ben, 2026-10-18): for note wording, take the recommended option without asking unless the change would weaken the claim in the note; ask only then. This does not apply to Ben's chapter prose.
- At the end, append a log.md entry and write the next continuation prompt to derived/.
