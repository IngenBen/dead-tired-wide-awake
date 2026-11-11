# Continuation prompt — Endnotes only

> Paste the block below into a new thread to continue the endnotes work.

---

ROLE & CONTEXT
You are the maintainer of the "Sleep Incorporated" book vault. Read `CLAUDE.md` in the project
root first and follow it exactly. `/book/` is the finished manuscript and is **read-only** — you
read it for context only; every proposed change is a proposal in `/audit/`, never an edit to
`/book/`. This thread is **endnotes only** — do not reopen claim decisions.

STATE (where things stand)
- The `claim-action-list.md` pass is **complete** — every flagged claim (Ch03–Ch24) has a decision
  applied. Prose edits live in per-chapter proposals `/audit/chNN-proposed.md`; accepted endnotes
  are collected in `/audit/endnotes-draft.md`.
- `endnotes-draft.md` holds **24 entries**, in chapter order (03 → 06 → 08 → 10 → 11 → 12 → 13 → 18
  → 19 → 20 → 22 → 23 → 24). Each entry states its decision type, its attach point, a short
  author-voice summary where relevant, and a `Sources:` list. Endnote markers `⟦EN:ChXX⟧` are
  placed in the `chNN-proposed.md` rewrites (claim-keyed, not yet numbered).
- A consistency sweep is done (ordering fixed, attach points complete, no orphan/missing markers).

NOTE ON TOOLING
- `endnotes-draft.md` has some very long lines and lives on OneDrive files-on-demand, so **bash
  reads can silently truncate it**. Use the file-reader (Read) and Edit tools for it, not shell grep.

REMAINING ENDNOTE WORK (in order)
1. **Firm up the weak citations** (no `/book/` edits — only `endnotes-draft.md` + the reference files):
   - **Ch22.7-8** — has *no* real citation (just "background physiology"). Pin a proper
     nocturia / nocturnal-polyuria + overnight-vasopressin reference. Keep the cortisol→bladder
     step flagged as the author's inference.
   - **Ch24.11-16-17** — (a) third source bullet is vague ("see Ch24.12/24.13 notes") → pin the
     glucose counter-regulation review already used at Ch24.12/13 (Front Neurosci 2014 8:38,
     PMC3935387). (b) second bullet is an unnamed *Nutrients* 2026 reactive-hypoglycaemia study
     (PMC12986748) → get author/title.
   - **Ch24.20** — verify the "Zopf Y et al. 2021" attribution for PMC8625578 (non-IgE food
     hypersensitivity / diagnostics review); correct if wrong.
   - **Ch24.21** — name the cross-sectional brain-fog study (PMC11857395): author, year, journal.
     NHS food-intolerance cite is fine.
   - **Ch23.13a** — Sleep Foundation + Northwestern Medicine are consumer-health bodies (fine for a
     popular book); optionally add one primary source for the carb→tryptophan / overnight-glucose
     point if firming further.
2. **Normalize citation format** — make every `Sources:` line a consistent style (author, year,
   *Journal* vol:pages, DOI). Replace bare ResearchGate / Amazon / Magtein.com / PubMed / Oura-blog
   URLs with DOIs or stable links where available (affected: Ch08.6 Berridge, Ch08 "Engineered
   highs", Ch10.21 Oura, Ch11.11 Sports Research/Magtein).
3. **Final compile (do LAST, likely a later thread)** — convert the claim-keyed markers
   (`⟦EN:Ch18.21⟧`) into sequential numbered notes and build a back-matter references section.
   This **depends on the author having hand-applied the `chNN-proposed.md` rewrites to `/book/`**
   first, because numbering must follow the manuscript's final reading order. Don't number until
   then.

METHOD for firming sources (follow the original sourcing-pass method)
- Reuse citations already in `/audit/claim-references.md` (HIGH), `claim-references-MED.md` (MED),
  and the `*-sources.md` / `*-working.md` companions before searching anew.
- To pin a new one: WebSearch to find the ID, then Europe PMC REST for the abstract/verbatim
  (`https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=EXT_ID:<PMID>&resultType=core&format=json`).
  **Avoid CAPTCHA-blocked pmc.ncbi.nlm.nih.gov.** Do a verbatim-quote + number check for anything cited.

HARD RULES
- Never edit `/book/`. Proposals only; endnote text stays in `/audit/endnotes-draft.md`.
- Don't invent sources. Keep the author's honest voice in "summary plus sources" endnotes (per
  CLAUDE.md) — a limitation noted plainly, not academic hedging.
- Use the task list; pause for my input between steps; append a `log.md` entry per step.

START by reading `CLAUDE.md` and `endnotes-draft.md`, give me a one-screen list of the soft
citations with what each needs, then begin firming them one at a time, pausing for my confirmation.
