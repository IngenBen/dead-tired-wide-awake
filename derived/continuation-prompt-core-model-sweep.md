# Continuation prompt — Core model sweep (2026-11-12)

Paste this into a new session to pick up where we left off. Follows `derived/continuation-prompt-core-model.md` (the rollout, now complete on the book side).

---

## Start here

1. Read `CLAUDE.md` in `C:\Projects\sleep-inc\Sleep Inc\Sleep Incorporated` and follow it exactly. Book edits are CriticMarkup tracked changes, only when I name the chapter and say go. This sweep is an AUDIT: findings go to `/audit/`, no markup in `/book/`.
2. Read **`derived/core-model.md`**. Its three-concepts table, "What each concept does" rules and "three jobs in company terms" table are the rules for this sweep.
3. Read `derived/author-style-notes.md` for voice, in case a finding needs a proposed rewording.

## Where the book stands

Rollout markup added 2026-11-12, pending Ben's review (may already be accepted when you start):

| Chapter | Lines |
|---|---|
| Ch03 | L26, L30, L32, L34, L40, L42; typos L48, L54, L60, L64, L66 |
| Ch04 | L7, L11, L61, L65, new paragraph L67, L71, L77, new paragraph L79 |
| Ch05 | L55 (typo) |
| Ch10 | L11, L13 |
| Ch11 | L46 |
| Ch17 | L40 |
| Ch20 | L25 |

Checkpoint commits: 7cb89d5, b81a163, and one after Ch10. First check `git status` and whether any CriticMarkup remains (`grep -n "{++\|{--\|{~~" book/*.md`). Ask Ben whether he has finished reviewing before starting. If markup is still pending, read the original text (CLAUDE.md rule) but mark the row **Pending markup** and note what the proposed text would change.

Decisions made in the 2026-11-12 rollout session (not yet in `core-model.md`):
- The CEO's action at Ch04 L7 is **setting the expectations**: when staff clock on, when they clock off, and a clean handover from the day shift to the night shift. Signals are not named at L7; they are introduced at Ch04 L79.
- Ch04 L77: calming system = "the day shift hands over cleanly to the night shift"; third job = "a CEO who stops calling the wrong executives in at the wrong times".
- Good-staff paragraph before "Not broken, just not well trained": "working hard" (not "overtime", which only fits the wake side).
- At 2am the handover has already happened; the calming system's job is to **hold the night** (Ch17 L40: "the night shift isn't over yet", mirroring Ch07 L79).
- Ch03: fitness only carries "not overnight". The order in L32 is answer first, fitness last ("A lot like getting fit."). "Over weeks" avoided early in the book. Ch03 L40 "Again, a bit like getting fit."
- Ch20 L25 rejects the single signal **in the moment**, not signals.
- Checked and left: Ch07 L53, Ch16 L11, Ch20 L29–33/L45/L53/L113–125, Ch21 L31, Ch22 L67, Ch26 L9, L35.

## The sweep

**Task:** Using the core concepts table in `derived/core-model.md`, list every place in the book that references either a concept or words associated with that concept. Then check whether each mention follows the rules for that concept. Output as a table showing chapter, wording in situ, and whether it follows the rule.

### Scope

- All chapter files in `/book/` (ch01–ch26). Then `book/endnotes.md` as a separate, lower-priority section (neutral voice; check only that it doesn't contradict the model).
- Use a script (grep with line numbers) to find candidates, then read each hit in context. Don't judge from the grep line alone.
- Skip literal uses that aren't the concept: e.g. "exercise" in Ch22 as the habit itself, "signal" in a purely biological sense in Ch05–08 where it isn't the CEO's lever (list these as **Literal** rather than leaving them out, so the count is complete).
- Work chapter by chapter, writing results to the file as you go (the table will be long). Stay involved: after every few chapters, post a short summary of the problems found so far.

### Search vocabulary

| Concept | Words to search |
|---|---|
| **Company** (the model) | company, Sleep Incorporated, CEO, executive(s), Sleep Executive, Wake Executive, manager(s), worker(s), staff, employee(s), hierarchy, consultant(s), A-team, business, org chart, turn around, culture |
| **Company — shifts** | shift(s), day shift, night shift, clock on, clock off, clocked, clocking, handover, hand over, take turns, roster, stand down, stands down, left the building, go home / going home, overtime, expectations, on time |
| **Signals** (the lever) | signal(s), signalling, activating, activated, calming, calm (as a label), setting(s), mode(s), side (activating/calming side), go-mode |
| **Training** (the change process) | train, trained, training, training program, practice, out of practice, reps, repetition, learn / learns (of the system), teach, taught |
| **Fitness** (illustration only) | fit, fitness, getting fit, muscle, strength, workout, push-ups, race, gym, shape (as in "in shape") |
| **Retired terms** (should not appear as concepts) | aligned, alignment, misalignment, align, three signals, culture, settings, sleep fit, broken (of a person), fix (as the right approach) |

### Rules to check against

From `derived/core-model.md`, plus the decisions above:

**Company**
- The company is the single model. Sleep is an output of the whole company / whole day.
- The CEO can't do the executives' jobs or place an order; the CEO sets the expectations.
- Clocking on and off covers **all four** executives. Don't narrow it to the wake side "going home" (wake-side-only wording is fine where the passage is specifically about cortisol or dopamine).
- Body clock = the roster. Calming system = the handover. Disruptors = calling the wrong executives in at the wrong time (both sides).
- The executives are good staff, not well trained. Never imply they are useless or broken.
- "Working together / against each other / as they should", not alignment.

**Signals**
- Two kinds only: activating and calming. Not a numbered framework; timing is when they're sent, not a third signal.
- Habits send signals. One signal changes little; the same signals every day are the training.
- Activating and calming stay as the book's labels: "activating system" and "calming system" (not "settings", "sides", "activated and calm"). Clock on and handover are the plain-English version. Never two competing models.
- A rejection of signalling must be a rejection of the single in-the-moment signal (Ch20 L25), not of signals.

**Training**
- Describes how change happens, never what sleep is.
- "Trained" is the book's word. "Practice" only as plain description, not a refrain. No "out of practice". No "reps".
- You send the signals; the company gets trained. The reader "training" a system (Ch20) is fine as plain description.

**Fitness**
- Illustration only: Ch03 for "not overnight", Ch20 (and its echoes in Ch21, Ch22) for the calming system as a muscle. Ch26 L9 accepted as a quick comparison.
- Never describes what sleep *is*. Executives don't do push-ups. Not a concept, not the thesis, no "sleep fit".

**Voice** (flag only if a proposed fix is needed): short sentences, Australian spelling, no em dashes in new text.

### Output

Write to **`audit/core-model-sweep.md`**. One table per concept (Company, Shifts, Signals, Training, Fitness, Retired terms), each with these columns:

| Chapter | Line | Wording in situ | Follows rule? | Rule / issue | Proposed action |
|---|---|---|---|---|---|

- **Wording in situ:** the phrase plus enough of the sentence to judge it (keep to about 25 words; quote the book exactly).
- **Follows rule?:** Yes / No / Borderline / Literal / Pending markup.
- **Rule / issue:** which rule it meets or breaks, in a few words.
- **Proposed action:** blank for Yes and Literal; for No and Borderline, a short suggestion (not markup).

Finish the file with:
1. **Summary counts** per concept (Yes / No / Borderline / Literal).
2. **Problems ranked by importance** (No first, then Borderline), each with chapter and line.
3. **Patterns** worth noting across chapters (e.g. a label that keeps drifting).

Then post the summary and the ranked problems in chat. Don't mark up `/book/` until I pick which to fix; then draft each in chat first (REWORD format from CLAUDE.md), one passage at a time.

## After the sweep

- Fixes agreed from the sweep → markup → review.
- Then the wiki stage from `derived/continuation-prompt-core-model.md` ("After the book changes are accepted"): rewrite `sleep-as-a-system.md` and `sleep-incorporated-metaphor.md` from `derived/core-model.md`, update `four-executives.md`, `calming-activating-systems.md`, `hormone-misalignment.md` and `index.md`, and move the decisions above into the `core-model.md` decision history.
- Log each operation in `log.md`.

## Housekeeping

Deletion isn't allowed in the connected folder, so git leaves lock files behind. Before each git command, move any `.git/HEAD.lock`, `.git/index.lock` and `.git/objects/maintenance.lock` aside to `.git/stale-*` (never under `.git/refs`), or ask Ben to allow deletion. Commit before each editing pass in /book/.
