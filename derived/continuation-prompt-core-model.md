# Continuation prompt — Core model rollout (2026-11-12)

Paste this into a new session to pick up where we left off. Replaces `derived/continuation-prompt-signals-reps-model.md` (now marked partly superseded).

---

## Start here

1. Read `CLAUDE.md` in `C:\Projects\sleep-inc\Sleep Inc\Sleep Incorporated` and follow it exactly. Book edits are CriticMarkup tracked changes, only when I name the chapter and say go.
2. Read **`derived/core-model.md`**. It is the reference for every decision below: the three concepts table, the pub version, the model sentence, the three jobs in company terms, and the rules for each concept. Check every draft against it.
3. **Work in chat first.** Draft and discuss (REWORD format from CLAUDE.md) before any markup. One passage at a time; wait for my agreement.

## The model in one line

The **company** is the model (four executives clocking on and off at the right times, with a clean handover between the day shift and the night shift). **Signals** are the lever (habits that send regular signals, activating or calming). **Training** is the change process (good staff, never well trained; the same signals every day). **Fitness** is an illustration only (Ch03 "not overnight", Ch20 muscle).

## Checks for every draft

- Clocking on and off covers **all four** executives. Don't narrow it to the wake side "going home". (I corrected this once already.)
- Calming system = **the handover**. Body clock = **the roster**. Disruptors = **calling the wrong executives in at the wrong time** (both sides: late coffee, phone, sugar; long or late naps, sleep-ins).
- Two signals, not a numbered framework. Timing is when they're sent, not a third signal.
- "Trained" is the book's word. "Practice" only as plain description. Avoid "out of practice".
- Fitness never describes what sleep *is*. You send the signals; the company gets trained. Executives don't do push-ups. No "reps".
- The executives are good employees: plenty of overtime, but the handover doesn't always show up when you need it. Never imply they are useless (keeps "not broken").
- Voice: `derived/author-style-notes.md`. Short sentences, Australian spelling, no em dashes in new text.

## Current state of /book/

- Accepted 2026-11-11: "aligned/misalignment" retired as a concept (working together / against each other / as they should) in Ch03, Ch04, Ch09; Ch05 L33 "teamwork problem"; Ch09 L5 fix.
- **Ch10 L13 has pending markup** (two settings → "Training is what teaches them to…"). Predates the model. **Recommend Ben rejects it**; L11–13 get redrafted (step 6).
- No markup anywhere else. Old signals wording removed from Ch04 is in git commit b110793 if needed.

## Next steps (in order, drafts in chat first)

**Ch04 sets up the model, so it comes first.**

1. **Ch04 L7.** Replace "shape the culture" with the CEO's real action: you can't do the executives' jobs, but you can set their shifts, through signals. Keep "you can't reach in and operate the machinery".
2. **Ch04 L11.** "Each one doing its best to align with the company culture": culture is no longer the frame. Rework towards each executive having its own shift / working together.
3. **Ch04 L65–67.** Add the good-employees idea (overtime, but the handover doesn't show up when you need it) before "Not broken, just not well trained." Must cover all four executives, not just cortisol and dopamine. (An earlier chat draft, "the part of the company that sends everyone home", was too narrow; don't reuse it.)
4. **Ch04 L75.** Already has the right shape ("so the executives know when to clock on and when to clock off. A strong calming system, so they actually do."). Consider replacing "a CEO who stops getting in their way" with calling the wrong executives in at the wrong time. Add one sentence tying signals to training if it isn't already carried by L7. Keep "None of it changes overnight. Like any training…".
5. **Ch03.** Fitness now only carries "not overnight".
   - L32: remove "the theory I started to form was:" so fitness illustrates the uncomfortable truth rather than being a discovery.
   - L26: drop "like recovering from an illness or an injury", so fitness is the single analogy for "not overnight".
   - L42–44 ("nobody taught us about sleep"): trim, probably harder than previously planned. This is where the analogy is stretched furthest.
6. **Ch10 L11–13.** Redraft "activated setting / the other one / two settings" around the two signals and the shifts (L11 already says "a system that never clocked off"). L15 (three jobs) likely stays; check it reads as what the signals achieve.

## Knock-on effects after Ch03, Ch04 and Ch10 are agreed

- **Ch05 L55:** the first payoff of the activating signal. Fix the typo "Every cup is sends".
- **Ch07 L53:** "activating and calming at their clearest" pays off the two signals. Ch07 L79 already uses signals to the Wake Executive.
- **Ch11 L46** "two modes, activated and calm" and **Ch17 L40** "activating side / calming side": bring the labels into line.
- **Ch16 L11:** first use of "activating system". Check it fits.
- **Ch20:** L45 "we've been calling them the activating and calming systems since the start": make it true. L25: confirm it rejects the single in-the-moment signal, not signals. Check the muscle image (L29 "strength problem", L53 "builds that muscle") sits comfortably beside workplace training. L121 "It will show up at two in the morning" is the handover payoff: keep.
- **Ch22 L67** "calming system getting a workout": optional.
- **Ch26 L35** ("get the four executives working together… turn the company around"): check it still fits the shifts framing.
- Fitness passages to re-test against "illustration only": Ch03 L32–40, Ch04 L75, Ch20 L29–33, L53, L63, L113–125, Ch21 L31, Ch26 L9.
- Already consistent, use as reference: signals in Ch07 L79, Ch18 L37–43, Ch19 L3 and L9, Ch20 L61, Ch23 L5; shift vocabulary in Ch07 L17/59, Ch09 L9, Ch17 L12, Ch18 L15/37/43, Ch19 L3/9/17/19, Ch20 L121, Ch22 L11/13, Ch25 L35.

## After the book changes are accepted

- **Wiki:** rewrite `sleep-as-a-system.md` (thesis page) and `sleep-incorporated-metaphor.md` from `derived/core-model.md`, removing their SUPERSEDED banners. Update `four-executives.md`, `calming-activating-systems.md` (the handover; clock on / clock off as plain-English labels), `hormone-misalignment.md` (rename or rewrite; misalignment retired), and `index.md`.
- **`derived/core-model.md`:** move answered open questions into the decision history.
- **Optional:** decide where the pub version and the "rostering problem" hook live (back cover, intro, `derived/content-ideas.md`). Ask me.
- Log each operation in `log.md`.

## Housekeeping

Deletion isn't allowed in the connected folder, so git leaves lock files behind. Before each git command, move any `.git/HEAD.lock`, `.git/index.lock` and `.git/objects/maintenance.lock` aside to `.git/stale-*` (never under `.git/refs`), or ask Ben to allow deletion. Commit before each editing pass in /book/.
