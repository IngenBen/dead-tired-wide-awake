Read CLAUDE.md first and follow it exactly. /book/ is read-only; write edit proposals to /audit/, never edit the book. Do not edit anything in derived/sources/, including endnote-review-log.md.

Context. We're working through the issues in derived/sources/endnote-review-log.md (Batches 1–14, 128 items). The working file is audit/endnote-review-triage.md. It has Groups A–G with a status on every item, a quick-wins section, a Decisions table, a follow-up list and a tally. Finished so far: the quick-win pass (44 items), the Group D pass, and the Group E pass (17 items; 14 DECIDED, 3 KEPT). Read the triage file in full before starting.

Status labels: the triage key (DECIDED / KEPT / FOLLOW-UP / PARKED / OPEN, + FLAG) is the record. The log's own tags (FIX, KEEP?, OPEN/KEEP/CHANGE/?) are the collector's first impressions only; KEEP? and FIX both mean "not yet reviewed".

This pass: Group C ("figure or wording slightly off from source"), all OPEN items in this order:
3.2, 3.4, 3.6, 4.1 (13-minute framing), 4.5, 4.6, 5.8 (the still-open optimal-vs-higher HRV point), 7.5, 11.8, 11.10, 12.1.
(Group B, 13 items plus N2, is the pass after this. Leave it unless I ask.)

How to run it:
- One item at a time, using AskUserQuestion.
- Before each question, read the log entry, the current note text in book/endnotes.md, and the matching source file in derived/sources/. Don't rely on memory. Quote the note's actual current wording.
- Full text: check the source file's `access` field. If it is ABSTRACT ONLY, try to read the full text before asking, and say plainly what you checked and what you found.
  - WebFetch is often blocked on PMC (CAPTCHA). The built-in browser pane (mcp__remote-devices__Claude_Browser__*) gets through PMC and open publisher pages: open one tab with preview_start, then navigate it and pull text with javascript_tool (document.body.innerText, regex for the key terms).
  - Do not get round bot-checks or paywalls (ScienceDirect "Just a moment", Ovid, Wiley). If blocked, try an open repository copy, the authors' institutional portal, or a reputable secondary source that reports the figure, and say it is a second-hand check.
  - If full text can't be reached, say so and include a "mark FOLLOW-UP" option.
  - Do not save new files to derived/sources/; record what the full text showed in the Decisions row.
- Explanation length: two to three times as long as a one-line table entry: what the note says, what the source says, and why it matters.
- Give 2–3 options, recommended first, with short descriptions. Where items in one note are closely linked, cover them in one question and say so (up to two questions per AskUserQuestion call is fine for linked notes).
- Check whether the chapter prose (book/chNN - *.md) relies on the point. If a note change would put the note out of step with the chapter, say so and offer to flag the prose (Group G). Give the chapter line number.
- If I ask a clarifying question instead of choosing, answer it plainly (use SendUserMessage if it needs more than a line), then re-ask. If I ask to pause, stop and wait until I say to return.
- If I ask for a better source, search for one (prefer systematic reviews or meta-analyses from developed Western countries), read it, and offer it as an option.
- After each decision, add a row to the Decisions table (insert before "### Follow-up list from this round") with a short in-place Python edit (the device shell's /tmp does not persist between sessions; don't write helper scripts into the project folders). Every few decisions, update the item's status in the Group C table. Add new issues as N-numbered items (N1 and N2 already exist), chapter flags to Group G, and new follow-ups to the follow-up list. Keep the tally current.
- At the end, append a log.md entry, e.g. ## [date] audit | endnote Group C decisions -> /audit/endnote-review-triage.md.

Preferences already set (apply them, don't re-ask):
- Citations keep the volume:pages style; long author lists use "First AB et al."
- Web pages stay undated, except the Sleep Foundation nap page.
- Prefer sources from developed Western countries.
- When the evidence creates tension with the chapter, put the most factual version in the Notes and offer to flag the chapter prose rather than bending the note. (I often decline a flag when the prose is already hedged; offer it, don't assume it.)
- When a statement is the book's own advice or reasoning, frame it that way rather than attributing it to a source.
- House style is summary plus sources: neutral encyclopedia voice, no statistics language in the summary prose (figures go in the source-line parenthetical). Remove meta lines that talk about "the book's framing" or "the claim is directionally correct" when a note is touched.
- Scope caveats (sample size, single study, population, exercise vs rest) usually go in the source-line parenthetical rather than the summary.
- Second-hand confirmation (e.g. OMIM, a later review quoting the figure) is acceptable when full text is blocked, provided the Decisions row says so.

Don't: fix anything in /book/. Don't do the FOLLOW-UP source lookups (8.11, 8.8/8.7, 11.7, N1, 5.5a, Fries 2009 for 4.7, 6.1 Svensson, 10.5 overcast daylight, 11.2 nasal breathing) or the PARKED rewrites (CBN, protein incl. 9.9, brain fog) in this pass unless I ask.

Housekeeping: audit/_to_delete/.addrow.py is a stray helper from the Group E pass; leave it for me to delete.
