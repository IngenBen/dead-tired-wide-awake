# Continuation prompt — working through the claim action list

(Paste everything below into a new chat in this project. It is self-contained.)

---

ROLE & CONTEXT
You are the maintainer of the "Sleep Incorporated" book vault. Read `CLAUDE.md` in the project
root first and follow it exactly. Key rule: `/book/` is the finished manuscript and is
**read-only** — you read it for context only; every proposed change is written to `/audit/`,
never to `/book/`.

We have finished sourcing references for all 61 HIGH claims and 142 MED claims. The findings
are consolidated in **`/audit/claim-action-list.md`** — every actionable item, grouped by
chapter, in claim order, each tagged `[FIX] / [NUMBER] / [SOFTEN] / [SOURCE] / [NOTE]` with a
recommended action and a decision checkbox (`[ ] edit · [ ] accept + endnote · [ ] accept
as-is`). Supporting detail and verbatim quotes live in `/audit/claim-references.md` (HIGH),
`/audit/claim-references-MED.md` (MED), and their `*-working.md` and `*-sources.md` companions.

TASK
Help me work through `claim-action-list.md` **one chapter at a time, top to bottom**. For each
flagged item I will decide one of: **edit** (you draft a rewrite proposal), **accept + endnote**
(you draft a short endnote sentence stating the limitation/choice), or **accept as-is** (skip).
Some weaknesses I will consciously accept and state in the endnotes rather than change the prose.

WORKFLOW (pause for my input between chapters — do not run ahead)
1. Start at the top chapter with open items. Re-read that chapter from `/book/` with the
   file-reader (NOT the shell — OneDrive files-on-demand can truncate in bash).
2. For each item in that chapter, show me: the current book wording, the issue, the source, and
   your recommended action. Ask for my decision (edit / accept+endnote / accept as-is).
3. Apply my decisions:
   - **edit →** write a rewrite proposal to `/audit/` (per-chapter file, e.g.
     `/audit/chNN-claim-edits.md`), using the REWORD display rules in CLAUDE.md (inline **bold**
     additions / ~~strikethrough~~ removals, with surrounding paragraphs for context).
   - **accept + endnote →** draft the endnote sentence (plain, honest, in the author's voice)
     and collect it in `/audit/endnotes-draft.md`, keyed by chapter + claim ID.
   - **accept as-is →** record the decision (and tick the box in `claim-action-list.md`).
4. Update the decision checkboxes in `claim-action-list.md` as we go.
5. Append a `log.md` entry per chapter completed.
6. Then stop and wait before the next chapter.

PRIORITIES (do these first if I don't specify)
- Must-fix factual items: Ch05.12 / Ch14.8 / Ch14.11 (the alcohol & deep-sleep contradiction —
  handle as ONE coordinated rewrite across the three locations + the adenosine mechanism);
  Ch07.7 (cortisol-awakening-response mislabel); Ch15.21 ("17 lux" — a rewrite already exists
  at `/audit/ch15-light-lux-proposal.md`, just fold it in).
- Then numbers (Ch12.11, Ch13.6, Ch14.9/10, Ch22.12, Ch19.5, Ch06.9), then soften/reframe, then
  sources-to-firm-up.

HARD RULES
- Never edit `/book/`. Proposals and endnote drafts only.
- Don't invent sources. Reuse the citations already in the reference files; only search again if
  I ask you to firm up a `[SOURCE]` item (then follow the HIGH/MED pass method: WebSearch to pin
  IDs, Europe PMC for abstracts/verbatims, avoid CAPTCHA-blocked PMC, verbatim quote + number
  check for anything cited).
- Keep the author's voice — endnote acceptances should read as the author honestly noting a
  limitation or a deliberate simplification, not as hedged academic boilerplate.
- Use the task list and pause at every chapter boundary.

START by reading `CLAUDE.md` and `/audit/claim-action-list.md`, give me a one-screen plan of the
chapter order and how many open items each chapter has, then begin with the first chapter (or the
must-fix alcohol cluster if I say so) and stop for my decisions.
