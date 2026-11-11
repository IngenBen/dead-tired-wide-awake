---
title: Chapter audit prompt
type: operational
status: active
---

## Usage

Paste this prompt into a fresh session, then append the chapter text where indicated. The prompt runs in two stages — beat analysis first, then category-by-category review — with a confirmation gate between each stage and between each category in stage two.

Output goes to a chapter-specific file: `C:\Users\bencm\AppData\Roaming\Claude\local-agent-mode-sessions\71d6e88c-c3bb-4abf-b1b0-1fa912ba51e1\6d6a8599-3d28-490a-8276-7a0663b8885d\local_935ba32c-e6c9-4542-ab09-75bd4d0fddb7\outputs\scratch-pad-chXX.md` (where XX is the chapter number). Each phase of the audit is appended to the same file — never overwritten. Only a brief summary appears in chat.

**Before using this prompt:** instruct Claude to:
1. Read `derived/author-style-notes.md`. All proposed rewrites must conform to the author's voice, tone, and structural patterns documented there — particularly: short sentences, stacked fragments over bullet lists, British/Australian spelling, qualified claims, symptom-first structure, and the register appropriate to the chapter type (memoir / explainer-with-grounding / phase chapter).
2. **Cross-chapter check — selective.** Only consult `index.md` for findings in these three categories: **Contradictions**, **Repetition**, and **Over-explaining**. For those, look up the relevant concept in the index, check its `appears_in` chapters, and read those chapters before proposing a fix. Skip the index entirely for **Cadence and flow**, **Weak points**, and **Abrupt transitions** — these are local to the chapter and cross-chapter context won't help.

---

## Prompt

Write all analysis output to `C:\Users\bencm\AppData\Roaming\Claude\local-agent-mode-sessions\71d6e88c-c3bb-4abf-b1b0-1fa912ba51e1\6d6a8599-3d28-490a-8276-7a0663b8885d\local_935ba32c-e6c9-4542-ab09-75bd4d0fddb7\outputs\scratch-pad-chXX.md` (replacing XX with the chapter number). Append each phase to the same file — never overwrite it. The user will view this in a side pane while discussing in chat. Provide only a brief summary in chat, directing the user to the file for the full analysis.

---

Consider the main messages in this chapter, then go beat by beat to determine whether

* each beat is relevant
* each beat pulls its weight
* no beat is re-explaining another beat.

Report only beats that have problems. Do not comment on beats that are working. For each problem beat, explain the issue and suggest a fix marked up using strikethrough and bold. Show the paragraphs immediately before and after the change.

Before presenting any recommendation, evaluate whether the proposed reword itself creates an abrupt transition or introduces repetition with surrounding text. If it does, revise the recommendation until it passes both checks, then present the final version only.

---

Once you've completed the above, stop and wait for confirmation before proceeding to the full review below.

---

Please review the following chapter across these six categories:

* **Contradictions** — internal logic or factual conflicts with earlier content
* **Cadence and flow** — rhythm, sentence variety, pacing
* **Weak points** — underdeveloped arguments, vague claims, or unconvincing passages
* **Over-explaining** — restating what's already clear, excessive hand-holding
* **Repetition** — repeated words, phrases, or ideas (within this chapter or vs. prior chapters)
* **Abrupt transitions** — jarring jumps between paragraphs or sections

For each category, find and report **every instance** in the chapter — do not limit yourself to one example. Number the issues within each category (e.g. Contradiction 1, Contradiction 2). If a category has no issues, state that clearly and move on — do not pad with observations about what is working.

For each issue: explain the problem, then suggest a rewrite showing the relevant passage with the paragraph immediately before and after for context. Show changes in **bold** and ~~strikethrough~~.

**Work through one category at a time.** After completing a category, stop and wait for confirmation before moving to the next one.

---

[PASTE CHAPTER HERE]
