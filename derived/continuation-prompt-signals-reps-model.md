# Continuation prompt — Signals + reps model (2026-11-11)

Paste this into a new session to pick up where we left off.

> **PARTLY SUPERSEDED 2026-11-12.** Use `derived/core-model.md` for the current model. Next-session hand-off is now `derived/continuation-prompt-core-model.md`. Superseded here: the model sentence, "a signal is a rep" as the bridge, fitness as one of the three concepts, and the reps condition. Still standing: two signals (not three), the three jobs as what the signals achieve, conditions 1, 2 and 4–6, the current state of /book/, and most of the knock-on list.

---

Read CLAUDE.md in `C:\Projects\sleep-inc\Sleep Inc\Sleep Incorporated` and follow it exactly. Book edits are CriticMarkup tracked changes, only when I name the chapter and say go. **Work in chat first: draft and discuss before any markup.**

## The decision we're building on

The book has three concepts. Each answers a different question, and they link through one bridge: **a signal is a rep**.

| Question | Answer | Concept |
|---|---|---|
| What makes sleep? | A company with four executives that you can't run by hand | Company |
| What do you actually do? | Send signals, either **activating** or **calming** | Signals |
| How does that change anything? | Like getting fit: each habit is a rep, and reps add up | Fitness / training *[now Training; fitness is an illustration only]* |

**Model sentence (working draft):** *[SUPERSEDED 2026-11-12: see `derived/core-model.md`]*
> You can't run the company by hand. What you can do is send it signals. Every habit sends one, activating or calming. One signal changes little, the same way one workout doesn't make you fit. But send the right ones at the right times, day after day, and you train the company to work together on its own.

**Why it holds:** *[Reps bridge SUPERSEDED 2026-11-12: the bridge is now "repeated signals are the training". The Ch20 L25, Ch03 L34 and Ch22 L49 points still hold.]*
- One rep does nothing. This answers Ch20 L25, which rejects "signal safety in the moment": a calming signal tonight is one push-up, not training.
- There's no "one thing", because a program has many exercises (Ch03 L34).
- Consistency beats intensity (Ch22 L49: "a gym session you… could repeat tomorrow").

**The correspondence (for checking consistency only; don't spell all of it out in the book):** *[Partly SUPERSEDED 2026-11-12: body clock = the roster; calming system = a clean handover; disruptors = calling the wrong executives in at the wrong time. See `derived/core-model.md`.]*
- Calming system = strength, the muscle (Ch20)
- Body clock = routine, training at the same time every day
- Disruptors = what undoes training (Ch03 L34: "drinking, smoking, eating badly")
- Activating / calming = effort / recovery (Ch07 L19 "Spike and return"; Ch03 L42 "Rest and recover")

**Conditions (so fitness doesn't get inflated again):**
1. Fitness only ever describes the **change process**, never what sleep *is*. The company is the model.
2. Keep the images apart. *You* do the reps and *the company* gets trained. Executives don't do push-ups.
3. Use "reps" once or twice (Ch04 or Ch10), not as a new term. The book doesn't use the word at the moment. *[SUPERSEDED 2026-11-12: reps not needed.]*
4. **Two** signals, not a numbered framework. Timing is *when* you send them (the body clock), not a third signal. That was the flaw in the old "three signals" version (activate / calm / timing), which duplicated the three jobs and was removed today.
5. The three jobs (train the body clock, build the calming system, remove the disruptors) are **what the signals achieve**, not a second list next to them.
6. Fitness is not "the theory" or a discovery. Ch02's discovery is that the daytime matters. Ch03's discovery is the hormone mechanism ("That was the mechanism").

## Current state of /book/

- Accepted today: "aligned/misalignment" retired as a concept and replaced with "working together / working against each other / working as they should" (Ch03, Ch04, Ch09). Ch05 L33 "teamwork problem". Ch09 L5 "hold it loosely" removed.
- **Ch10 L13 still has pending markup** (the "two settings… Training is what teaches them to" change). It predates this model, so recommend Ben rejects it. Ch10 L11–13 will be redrafted around the two signals.
- The old signals wording that was removed from Ch04 L7/L9/L11/L65/L73/L77 is in git commit b110793 if needed for reference.

## Next step

Draft in chat (no markup yet), together, because they set up the model:
1. **Ch03 L32:** remove "the theory I started to form was:" so fitness illustrates the uncomfortable truth rather than being a discovery. For example: "…it became clear that the key to good sleep is not finding something that will finally flip a switch. It's much more like getting fit…"
2. **Ch03 L26:** drop "like recovering from an illness or an injury", so fitness is the single analogy for "not overnight".
3. **Ch04 L7:** *[UPDATED 2026-11-12: the CEO's action is setting the shifts; signals are how. See `derived/core-model.md`.]* bring back signals as the CEO's lever. Two kinds, activating and calming. Keep "you can't reach in and operate the machinery" and keep "working together" as the goal.
4. **Ch04 L75:** *[UPDATED 2026-11-12: keep the clock on / clock off shape already there; consider replacing "stops getting in their way". See `derived/core-model.md`.]* the three jobs as what the signals train. Keep "None of it changes overnight. Like any training…" and add the one sentence tying signals to reps.
5. Optional: **Ch03 L42–44** trim. This is where the fitness analogy is stretched furthest (the "nobody taught us" argument, not about time).

## Knock-on effects after Ch03/Ch04 are agreed

- **Ch04 L11** "align with the company culture" and L65 "nothing in my day had ever helped them work together": consider whether signals belong there (the old text had "listening for particular signals" and "sent the right signals").
- **Ch05 L55:** "activating signal… needs to be calming" becomes the first payoff. Fix the typo "Every cup is sends".
- **Ch07 L53:** "This is activating and calming at their clearest" pays off the two signals.
- **Ch10 L11–13:** replace "activated setting / the other one / two settings" with the two signals. Ch10 is also a good place for the single "reps" line if it isn't in Ch04.
- **Ch11 L46** "two modes, activated and calm" and **Ch17 L40** "activating side / calming side": bring the labels into line.
- **Ch16 L11:** first use of "activating system". Check it fits.
- **Ch20 L45** "since the start": make it true. Ch20 L25: confirm it reads as rejecting the single in-the-moment signal, not signals.
- **Ch22 L67** "calming system getting a workout": minor stray (not a "why isn't this quick?" moment). Optional.
- Fitness passages that pass the test and stay: Ch03 L32–40, Ch04 L75, Ch20 L29–33, L53, L63, L113–125, Ch21 L31, Ch26 L9.
- Signals already used in the program chapters in this sense: Ch07 L79, Ch18 L37–43, Ch19 L3 and L9, Ch20 L61, Ch23 L5.
- **Wiki after acceptance:** hormone-misalignment (rename or rewrite; misalignment retired), sleep-as-a-system (thesis page), four-executives, sleep-incorporated-metaphor, calming-activating-systems, index.md. Log that this reverses the 2026-11-11 "retire three signals" decision (now two signals) and reframes the 2026-09-24 fitness-as-thesis decision (fitness is now the change-process analogy).

## Housekeeping

Deletion isn't allowed in the connected folder, so git leaves lock files behind. Before each git command, move any `.git/HEAD.lock`, `.git/index.lock` and `.git/objects/maintenance.lock` aside to `.git/stale-*` (never under `.git/refs`), or ask Ben to allow deletion.
