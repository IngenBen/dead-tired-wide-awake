Read CLAUDE.md first and follow it exactly. /book/ is read-only (including /book/endnotes.md): write proposals and clean copies to /audit/, never edit the book. Do not edit derived/sources/endnote-review-log.md.

Context (state at 2026-10-20, 07:00). Read the last five entries of log.md before starting.
- All five source-summary flags are CLOSED (Riley 2024, Saleska 2024, WHO noise: already fixed by decisions 9.8, 1.1–1.3, 8.1; Zaplatosch 2020: no change; Lovallo 2005: no change, notes keep '48 men and 48 women' = 96 analysed, Ben 2026-10-20 'Keep simple ignore conflict. Use 96.'). Nothing further to raise on them.
- At 2026-10-20 14:00, /book/endnotes.md had a small edit by Ben (02:54 UTC) but is not the clean copy (not merged) and the chapter files 16 Oct (Group G rewordings not applied).

Carry on with derived/continuation-prompt-after-kb-sync.md:
- Step 1, once Ben says he has merged audit/endnotes-clean-2026-10-19.md: compare by script, then (asking before any file moves) archive, update CLAUDE.md and the catalogue counts.
- Step 2, once Ben says he has applied the Group G rewordings: full clean chapter copies with sections 1–26 applied (section 5 withdrawn) are in audit/group-g-clean/ (15 chapters + _diff.md, built 2026-10-20 by $HOME/work/gg_apply.py). First compare each /book/ chapter with its clean copy by script (whitespace-insensitive); identical = APPLIED. For any that differ, run the section-by-section check from the after-kb-sync prompt and report Ben's own changes without 'fixing' them. Archive audit/group-g-clean/ with the proposals file only after asking Ben.
- Step 3, only if Ben asks: untagged KB stragglers and the three unsaved sources.
- Step 4: CLOSED (Zaplatosch).
Steps 1 and 2 can run in either order. If Ben hasn't done either yet, say so and ask which he'd like to do first; don't run the checks against unchanged files.

Explaining to Ben: plain language for non-scientific readers. For any note or chapter question give (a) what the chapter says, quoted, (b) what the note says, (c) the conflict in one or two sentences, then the recommendation. One item at a time; wait for his answer.

Standing instructions and preferences from derived/continuation-prompt-after-kb-sync.md still apply. Helper scripts live in $HOME/work/ (may be gone; rewrite if needed), never in the project folders. Assert each old string occurs once before replacing. Append a log.md entry per stage and write the next continuation prompt to derived/ at the end.
