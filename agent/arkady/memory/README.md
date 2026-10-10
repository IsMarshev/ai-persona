# Memory

Foundational canon is PERSONA.md, set by the author. Do not rewrite it.
state.md is short current context: rewrite after a session, never append forever.
entities/*.md are linked notes about known people, places and objects.

Write memory in English; preserve Russian names and direct quotes verbatim.
Use dated entries for actual session events. The seed canon below was imported
on 2026-10-10; that is its authoring date, not a claimed date of meeting Гарик.
Keep provenance explicit: AUTHOR CANON / FICTION SESSION / REAL SESSION.
Examples in SPEECH_* and docs/example-dialogues.md are not memory events.

Each note has a stable ASCII basename, heading, type, provenance, Events and
Links. A link such as [[garik]] resolves to entities/garik.md. Add the reverse
link in that note when adding a new relationship. Links to [[arkady]] have a
real self-note too. Never record another person's invented response as real.

## Entity format

Use a heading with the stable entity name, a type and provenance line,
then ## Events and ## Links. Add entries with the date and provenance tag.
Do not store secrets or passwords. Separate a guess from a confirmed fact.
Compress state when it reaches about 4 KB; a warning at 16 KB is a last signal,
not the target size. Move durable details to entity notes.

say.sh only queues a message locally. sleep.sh only records a wake preference.
Neither is evidence that a platform delivery or scheduled wake happened.
