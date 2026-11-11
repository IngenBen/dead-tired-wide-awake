Read CLAUDE.md first and follow it exactly. /book/ is read-only; write edit proposals to /audit/, never edit the book. Do not edit anything in derived/sources/, including endnote-review-log.md.

Context. We're working through the issues in derived/sources/endnote-review-log.md (Batches 1–14, 128 items). The working file is audit/endnote-review-triage.md. It has Groups A–G with a status on every item, a quick-wins section, a Decisions table, a follow-up list and a tally. Finished so far: the quick-win pass (44 items), the Group D pass, the Group E pass (17 items), and the Group C pass (11 items; 10 DECIDED, 1 KEPT), plus two citation checks (6.1 Svensson closed, Ellithorpe 2022 confirmed). Read the triage file in full before starting.

Status labels: the triage key (DECIDED / KEPT / FOLLOW-UP / PARKED / OPEN, + FLAG) is the record. The log's own tags (FIX, KEEP?, OPEN/KEEP/CHANGE/?) are the collector's first impressions only; KEEP? and FIX both mean "not yet reviewed".

This pass: Group B ("source doesn't support the note / wrong or missing source"), all OPEN items, in this order:
1.4, 2.1, 2.2, 3.7 with 4.4 (3.7 covers six notes; 4.4 is the same high-dose melatonin note, whose first sentence was left for this pass under 4.5), 8.9, 8.12, 9.2, 10.6, 10.7, 12.6, 12.7, 13.7 with N2 (same Ch25 background-immune note; fix the non-encyclopedia lines in house voice).
Leave the PARKED rewrites (Ch3 CBN incl. 1.3, Ch16 protein incl. 9.9, Ch25 brain fog) and the FOLLOW-UP lookups (8.11, 8.8/8.7, 11.7, N1, 5.5a, 10.5, 11.2) unless I ask. Where a Group B item overlaps one of them (e.g. 8.12 and 8.11 share the SHF/WHO Ch15 notes; 8.9 and N1 are both Ch14 caffeine), say so and decide only the Group B point.

Group B items usually need a different or extra source, not just a reword. Expect to search: prefer systematic reviews, meta-analyses or national bodies from developed Western countries; read the source before offering it; offer "drop the claim" or "frame as the book's own advice" as options where no good source exists.

How to run it:
- The project folder on my computer must be connected first: request access to C:\Users\bencm\OneDrive\Documents\Claude\Brain\Sleep Incorporated with device_request_folder_access, then work in it with device_bash ($HOME/mnt/Sleep Incorporated).
- One item at a time, using AskUserQuestion.
- Before each question, read the log entry, the current note text in book/endnotes.md, and the matching source file in derived/sources/. Don't rely on memory. Quote the note's actual current wording. Check whether an earlier decision already changed part of the same note.
- Full text: check the source file's `access` field. If ABSTRACT ONLY (or a web page saved only in part), try to read the full text before asking, and say plainly what you checked and what you found.
  - What worked last pass: open copies in university repositories (Monash, Stirling, ACU, Delaware, Adelaide), course copies, PMC via the built-in browser (mcp__remote-devices__Claude_Browser__*: open one tab with preview_start, navigate it, pull text with javascript_tool on document.body.innerText with a regex for the key terms), FASEB/PLOS/Frontiers pages, and the Crossref API (api.crossref.org/works/<doi>) for citation details.
  - Do not get round bot-checks or paywalls (ScienceDirect "Just a moment", Ovid, Wiley, Springer), and don't use unofficial uploads (Scribd and the like). If blocked, try an open repository copy, the authors' institutional portal, or a reputable secondary source that reports the figure, and say it is a second-hand check.
  - If full text can't be reached, say so and include a "mark FOLLOW-UP" option.
  - Do not save new files to derived/sources/; record what the full text showed in the Decisions row.
- Explanation length: two to three times as long as a one-line table entry: what the note says, what the source says, and why it matters.
- Give 2–3 options, recommended first, with short descriptions. Where items in one note are closely linked, cover them in one question and say so (up to two questions per AskUserQuestion call is fine).
- Check whether the chapter prose (book/chNN - *.md) relies on the point. If a note change would put the note out of step with the chapter, say so and offer to flag the prose (Group G), as its own question, with the chapter line number. Also check other chapters for the same claim (last pass found Ch23 line 25 repeating a Ch8 point).
- If I ask a clarifying question instead of choosing, answer it plainly (use SendUserMessage if it needs more than a line), then re-ask. If I ask to pause, stop and wait until I say to return.
- If I ask for a better source or more support, search for one (systematic reviews or meta-analyses from developed Western countries first; respected theoretical frameworks are fine if labelled as such), read it, and offer it as an option.
- After each decision, add a row to the Decisions table (insert before "### Follow-up list from this round") with a short in-place Python edit (the device shell's /tmp does not persist between sessions; don't write helper scripts into the project folders). Every few decisions, update the item's status in the Group B table. Add new issues as N-numbered items (N1 and N2 exist; next is N3), chapter flags to Group G, and new follow-ups to the follow-up list. Keep the tally current.
- At the end, append a log.md entry, e.g. ## [date] audit | endnote Group B decisions -> /audit/endnote-review-triage.md, and write the next continuation prompt (parked rewrites) to derived/.

Preferences already set (apply them, don't re-ask):
- Citations keep the volume:pages style; long author lists use "First AB et al."
- Web pages stay undated, except the Sleep Foundation nap page.
- Prefer sources from developed Western countries.
- When the evidence creates tension with the chapter, put the most factual version in the Notes and offer to flag the chapter prose rather than bending the note. (I often decline a flag when the prose is already hedged; offer it, don't assume it.)
- When a statement is the book's own advice or reasoning, frame it that way rather than attributing it to a source.
- House style is summary plus sources: neutral encyclopedia voice, no statistics language in the summary prose (figures go in the source-line parenthetical). Remove meta lines that talk about "the book's framing" or "the claim is directionally correct" when a note is touched.
- Scope caveats (sample size, single study, population, exercise vs rest) usually go in the source-line parenthetical rather than the summary.
- Don't add summary sentences that undercut our own sources just because they weren't tested in exactly the book's scenario (e.g. "No study has measured this during scrolling"); keep that kind of scope note in the parenthetical.
- When a note mixes supporting and balancing evidence, put the supporting studies first (summary and source list), then the balance.
- When people respond differently, say so (individual differences are welcome in the summary).
- Second-hand confirmation (e.g. OMIM, PubMed competing-interest records, a later review quoting the figure) is acceptable when full text is blocked, provided the Decisions row says so.

Don't: fix anything in /book/. Don't do the FOLLOW-UP lookups or the PARKED rewrites in this pass unless I ask.

Housekeeping: audit/_to_delete/.addrow.py is a stray helper from the Group E pass; leave it for me to delete.

After Group B, the remaining stages are: parked rewrites (CBN, protein, brain fog) → FOLLOW-UP lookups → my review of the Group G chapter flags → apply all decisions to derived/claims-knowledge-base.md → compile a clean Notes copy in /audit/ (check cross-references, headings and citation style) → housekeeping (decide on saving new sources, update CLAUDE.md counts, delete the stray helper).
