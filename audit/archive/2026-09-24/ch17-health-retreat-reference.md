# Audit — Chapter 17 ("Your Evening Routine"), orphan reference

Run: 2026-06-14. Single-finding audit prompted by author. Proposals only — `/book/` is read-only.

---

## ORPHAN REFERENCE — "the health retreat version"

**O1 (3/5) — Line 13. A callback to a passage that no longer exists.**

`ch17` line 13 currently reads:

> This is probably closer to most people's reality than **the health retreat version**. The evening is already spoken for...

The phrase "the health retreat version" is written as a callback — it assumes the reader
has already met an idealized, design-it-from-scratch evening wind-down (the unhurried,
whole-evening-is-yours ritual a wellness retreat would prescribe). **No such passage exists
anywhere in the manuscript.** A full sweep of `/book/` for the idealized-evening idea
(`retreat`, `wind down`, `ideal`, `perfect evening`, `from scratch`, `candle`, `incense`,
`herbal tea`, `journal`, `bath`, `lavender`, `wellness`, `ritual`, `sanctuary`, etc.)
returns nothing in any other chapter that sets this contrast up.

So the reader is asked to compare against something the book never shows them.

### Nearest surviving analog

The only place the book runs this exact rhetorical move — idealized/wellness-cliché version
vs. the author's stripped-back practical reality — is **ch12 ("Your Sleep Environment"),
line 7**:

> I didn't approach my bedroom environment the way the internet suggested — a 'sleep
> sanctuary' complete with incense, candles and sounds of the rainforest. I just looked at
> the obvious things...

(Compare also ch18:10, where meditation is framed as the "wellness cliché" the program
earns its way up to. Same family of move; not the same target.)

### Two readings

1. **It was always meant to echo ch12's "sleep sanctuary."** If so, the wording simply
   doesn't connect — "health retreat version" gives the reader nothing to link back to
   "sleep sanctuary," so the callback misfires. Fix = align the terminology.
2. **An idealized "perfect evening routine" passage once lived in ch17 (or a draft of it)
   and was moved or cut**, taking the near half of the contrast with it and stranding the
   "health retreat version" line. Fix = restore a one-line sketch of that idealized evening,
   or make line 13 self-contained.

Either way the underlying defect is the same: **half of a comparison is missing.**

---

## Proposed fixes (pick one)

### Option A — make line 13 self-contained (lightest touch)

Reword so the idealized version is sketched in-line and needs no prior setup. Context shown:
previous paragraph, amended paragraph, following paragraph.

Previous (unchanged):

> My evenings have a shape that isn't exactly negotiable. Dinner, homework, then getting
> three kids to bed. By the time the last one is down, the window between that moment and my
> own reasonable bedtime is not particularly long. Whatever the evening habit was going to
> look like, it had to fit inside that window — not replace what came before it.

Amended (line 13):

> This is probably closer to most people's reality than ~~the health retreat version~~ **the
> version you read about online — the unhurried evening that's yours to design from scratch,
> dim and screen-free for hours before bed**. The evening is already spoken for. There are
> things that need doing — a household that doesn't wind down on command. The question isn't
> how to design the perfect evening from scratch. It's what to do with the time that's left
> once the evening has happened.

Following (unchanged):

> For most people, that window exists. It might be 30 minutes. It might be an hour. It
> doesn't need to be more than that.

*(Note: this option also exposes a small in-paragraph repeat — "from scratch" would then
appear twice in two sentences. If A is chosen, change the second to "...how to design the
perfect evening" and drop the trailing "from scratch.")*

### Option B — align with ch12's existing "sleep sanctuary" framing (best if no passage was moved)

> This is probably closer to most people's reality than ~~the health retreat version~~ **the
> sleep-sanctuary evening the internet sells you**. The evening is already spoken for...

Trades on language the book has already established in ch12, so the callback actually lands.

### Option C — restore the moved passage (only if reading 2 is correct)

If an idealized-evening passage was genuinely relocated, the cleanest fix is to reinstate a
short version of it *before* line 13 so "the health retreat version" has a referent again.
Author to confirm whether such a passage existed and where it went — I found no trace of it
in the current `/book/`.

**Recommendation:** Option B if nothing was moved (lowest risk, reuses an established
contrast); Option A if you'd rather keep ch17 standalone. Confirm reading 2 before
considering C.
