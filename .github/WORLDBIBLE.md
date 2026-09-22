# World Bible

> **For future engineering sessions.**
>
> This document is intentionally not a player-facing roadmap. The discoveries should be experienced in the site, not announced here or explained in advance.

## Why this world exists

This began as Uncle John's birthday gift to Alayna: a small interactive adventure built around curiosity, courage, kindness, imagination, and strength.

The emotional center is more important than any puzzle. Alayna is quiet and curious. The experience should never treat quietness as smallness. It should reinforce that curiosity is a strength, that she comes from strong people, that she is loved, and that the person she becomes gets to be wonderfully her own.

The original birthday experience is the foundation. Future development must preserve it rather than replace it.

## The governing idea

**Never announce a new level. Let the world change.**

The player should discover development through observation: an object behaves differently, a light appears where there was darkness, an old symbol gains meaning, or something familiar becomes newly important.

The site should reward noticing, returning, remembering, experimenting, and patience more than random tapping.

A discovery should feel like *she found it*, not like the interface delivered it to her.

## Canon so far

The birthday quest introduces five powers and ends with the idea that the magic was already in Alayna.

A hidden paw created the first layer beyond the birthday quest. The secret trail established that curious minds notice what other people walk past.

After that discovery, the castle—present in the world from the beginning—awakens. Its door is locked. The player receives only:

> Some doors don't open the first time you find them.

The castle is therefore not a new decoration. It is the first proof that familiar parts of the world can acquire new meaning.

## Rules for future discoveries

1. **Preserve wonder.** Avoid obvious level announcements, quest logs, countdowns, or exposition.
2. **Earned, not hidden unfairly.** Clues can be subtle, but a thoughtful player should eventually be able to connect them.
3. **Return visits matter.** Some changes may occur only after a discovery, after time has passed, or on a later visit.
4. **Old objects may become new clues.** The five gems, castle, stars, paw prints, heart, sky, and other established elements form a visual language.
5. **No punishment.** Wrong guesses may redirect or reset a small puzzle, but never erase meaningful progress.
6. **Keep the birthday heart.** Cleverness must never overtake warmth.
7. **Do not make surveillance part of the magic.** If telemetry is added, keep it minimal and anonymous: milestone events only, with no location, fingerprinting, messages, or unnecessary personal information.
8. **Accessibility is canon.** Sound can enrich a clue but must never be the only path. Respect reduced motion and ordinary browser/device limitations.
9. **Do not overbuild.** A single changed window can be more powerful than a new screen full of features.
10. **Leave something unexplained.** Completion may answer one question while quietly creating another.

## Discovery architecture

Treat the experience as a small persistent world rather than a sequence of pages.

Local browser state can remember discoveries and alter the world on future visits. If a backend is later connected, it should record only coarse anonymous milestones such as return visit, secret discovery, or castle discovery. The game must remain playable if that backend is unavailable.

State changes should be additive and backward-compatible. A returning player should never lose the original birthday experience.

## Future-development envelope

Future chapters may explore the castle, reinterpret the original five powers, introduce environmental changes, make time and return visits meaningful, or allow apparently decorative objects to become part of a larger language.

The castle does not need to be merely a destination. It can become a hub, a boundary, a keeper of memories, or evidence that the world itself is responding to what Alayna notices.

The five original powers also do not have to remain static achievements. They can become keys, lenses, tools, or principles used to understand later mysteries—without undoing what they originally meant.

There is room for the world to grow across birthdays and ordinary days rather than becoming a one-week novelty. It could eventually hold small seasonal discoveries, messages from Uncle John, puzzles that reward curiosity, a private constellation of completed adventures, or chapters that mature with her.

But expansion is not the objective. **Meaning is.**

## Release discipline

Before every change, preserve a known-good commit, make one narrative change at a time when practical, test the complete discovery path on mobile Safari, verify persistent state after refresh, and avoid breaking already-earned discoveries.

When a chapter is working, stop. Give the player room to discover it before building over it.

## The long horizon

This can become more than a birthday page without ever needing to announce that transformation.

Years from now, the meaningful artifact would not be a complicated game. It would be a little digital place Alayna remembers as something her uncle made for her—one that kept changing because she kept looking.

Technology will change. The implementation can be replaced.

The promise underneath it should remain:

**Keep looking. There is always more to discover.**
