# Sweep: "misaligned/alignment" and "build" (2026-11-09)

Proposals only. `/book/` untouched. Context: the Option C discussion. *Misaligned* is a description that always comes with its cause (not well trained). It is never a problem with its own fix.

## ⚠ Flag first: Ch04 L67 one-liner has reverted

Ch04 L67 now reads **"Not broken, just misaligned."** Thesis Decision 1 (2026-09-24) replaced it with "Not broken, just not well trained.", and the log records it as applied. The ch04 file was last changed 2026-10-15, so the revert came later. The one-liner now appears only at Ch20 L29. Was the revert deliberate?
**Proposed:** restore "Not broken, just not well trained." at Ch04 L67. This is the most important line for Option C. It is where *misaligned* first gets handed over to *training*.

## Part 1: misaligned / alignment (22 uses)

### A. Description of the mechanism: fine, leave (15)
Ch03 L70, L76 · Ch04 L37, L39, L53, L57, L59, L65, L82 (footnote) · Ch05 L33 · Ch09 L11, L15 · Ch06 L25 (a different sense: two signals lining up = the window).
L65 already ends with the cause ("nothing in my day had ever sent the right signals to help them line them up"). That is the Option C pattern.

### B. Training/habits attached: already on Option C (5)
Ch03 L80 ("habits that keep them aligned") · Ch09 L93–95 (the model passage) · Ch16 L31 · Ch26 L35.

### C. Alignment framed as the task: Option A risk (3)
| Loc | Text | Issue | Proposal |
|---|---|---|---|
| Ch04 L41 | "the key was to align them" | Makes aligning the job, with no "how" | Optional: "the key was to get them lined up" and leave the "how" for L65–67. Low priority once L67 is restored. |
| Ch04 L55 | "work on the deeper alignment issues" | Problem label without training | "while you train the system underneath" (or "...work on the habits underneath") |
| Ch02 L41 | "the whole system was out of alignment" | Comes before the concept is introduced; informal | Leave. It reads as plain English, not a term. |

**Verdict:** Option A load is small. Two-thirds of uses are mechanism description. The real gap is Ch04 L67 (plus L55). Once those are fixed, every point where *misaligned* turns into "what do I do?" is answered with training.

## Part 2: build / built / rebuild (60 uses)

Suggested rule, which matches the fitness analogy and `derived/naming-sleep-builders.md` ("You build your sleep fitness (the result)"): **train = the activity, applied to a system. build = the result (strength, capacity, a habit, the sleep), or making a thing (the program).** You train *to* build, which is how the gym talks. Under that rule, most "build" uses are already correct.

### Leave: literal or physiological (21)
Adenosine/pressure building: Ch04 L21, Ch05 L19/29/33/63, Ch09 L15/44, Ch14 L20/22, Ch18 L11/43, Ch21 L15. "Built to / built itself": Ch06 L61, Ch07 L71, Ch08 L25/55, Ch10 L13, Ch03 L50, Ch22 L19. Ch17 L28 (brain builds connections). Ch01 L31 "how I was built" is a deliberate callback, so keep.

### Leave: the author building the program (6)
Ch02 L45, L51, L55, L59 · Ch10 L21 · Ch25 L65. You build a program; you don't train one.

### Leave: building habits / progress (10)
Ch08 L27, Ch10 L17, Ch11 L18/24, Ch12 L56, Ch17 L56, Ch18 L21/23, Ch20 L43, Ch26 L23. "Train a habit" would read oddly.

### Leave: building strength/capacity/sleep as the result (12)
Ch03 L32 · Ch13 L49 · Ch20 L29, L41, L53, L73, L125 · Ch21 L31 · Ch22 L61 · Ch26 L9, L11 · Ch10 L15.
These are fitness words: build muscle, build capacity. Ch10 L15 and Ch26 L11 pair "train the body clock" with "build the calming system". Clock = timing (trained), calming system = strength (built). That split holds up.

### Check: training language vs construction language (5)
| Loc | Text | Note | Proposal |
|---|---|---|---|
| Ch20 L1 | Phase 4 heading "Build your nervous system" | L3 says "train your nervous system". The system is the thing trained. | **"Train your nervous system"** (heading), L3 → "...training your nervous system: building the calm..." or keep L3 as is |
| Ch03 L60 | "what is the foundation, and how do we build it?" | Construction image (foundation) inside a fitness argument | Optional: leave. Foundation is used throughout Ch02–04 as plain English. |
| Ch03 L82 | "That foundation can be built." | Same | Optional: "That foundation can be trained." reads oddly, so leave. Or close the chapter on training: "That foundation can be trained into place" (not recommended). |
| Ch04 L55 | "build the foundation first" | Same | Leave |
| Ch22 L47/L69/L73 | build on / build to two / build the comedown | Everyday use | Leave |

**On foundation:** it's a third image alongside the company and fitness. It's light and appears only in Ch02–04 and Ch26 L23. Changing it would mean reworking the Ch02–03 argument ("tips only work on a foundation"), and that argument works. Not recommended.

## Summary of proposed edits
1. **Ch04 L67:** restore "Not broken, just not well trained." (high)
2. **Ch04 L55:** "deeper alignment issues" → "while you train the system underneath" (medium)
3. **Ch20 L1:** Phase 4 heading → **"Build your calming system"** (revised; see Part 3)
4. Ch04 L41: optional

## Part 3: "calming system" / "nervous system" (added 2026-11-09)

**What each noun does in the book.** *Nervous system* = the whole thing, with two modes (defined at Ch20 L45). *Calming system* = the half that is weak and needs strengthening: the "muscle" (Ch20 L53). The vagus nerve is the calming system's anatomy (Ch20 L55–63), not a third term.

**Verbs in use**
- Nervous system: **train** at Ch19 L45, Ch20 L3, Ch20 L33 ("strength training"), Ch21 L31, Ch22 L59. **Build** appears only in the Ch20 L1 heading. That makes the heading the only outlier.
- Calming system: **build** at Ch10 L15, Ch20 L73, Ch22 L61, Ch26 L11 · **train(ed)** at Ch10 L13, Ch20 L29, Ch22 L11, Ch22 L61 · **strong / strengthen / weak** at Ch10 L11/13, Ch20 L29/51/53/123, Ch22 L13/19 · **workout / session** at Ch21 L39, Ch22 L67.

**Rule (the gym pattern):** *train the nervous system → build (strengthen) the calming system.* You train your body and you build muscle. Both verbs are correct for the calming system: train = the activity, build/strong = the result. No changes are needed in the body text.

**Phase 4 heading.** The phase headings already follow the three jobs from Ch10 L15 ("Train the body clock. Build the calming system. Stop activation at the wrong times."): Phase 3 "Train your body clock"; Phases 2/5 "Remove ... disruptors" (stop activation). So Phase 4 should be **"Build your calming system"**. That matches Ch10 L15 and Ch26 L11 word for word and keeps "build" with the calming system. L3 then explains it: "train your nervous system: building the calm and tempering the activation". Trade-off: the heading names only the calm half, and Phase 4 also tempers activation (evening intensity in Ch22). L3 covers that, and Ch10 counts stopping activation as a separate job anyway.
Alternative: "Train your nervous system" (matches L3 and covers both halves, but breaks the echo of the three jobs).

**Other notes**
- Ch22 L21 "The calming system is already compromised": a fault word (Decision 2/3 spirit). Proposed: "already weak" or "already undertrained".
- Ch06 L49 "Calm the nervous system": an in-the-moment verb, used before the training frame is introduced. Leave.
- Ch21 L31 "nervous system training" / L39 "calming system session": fine; both are training sessions.
