# The engine

Work began on 23 January 2026, before any interface.

## Why first

The promise that an unedited file returns its original bytes cannot be kept by
an interface. It is kept, or broken, by the part that reads and writes files.
That part came first, with no screen attached.

## What it models

A screenplay is not text with formatting. It is a stream of typed elements —
scene heading, action, character cue, dialogue, parenthetical, transition,
shot, general, centred, lyrics — and the parts that never print: notes,
sections, synopses, page breaks.

Production data is modelled as itself. A scene number is an address a schedule
cites, not a string typed into a heading. An omitted scene is a record that can
be reversed, not deleted text. Both then survive editing, reordering and a
round trip through other software.

## Constraints

No network. No telemetry. No file-system access. Nothing that re-serialises a
document wholesale on save.

## Open

Which formats the engine would speak, and in what order. Final Draft
documents, which is what working writers are handed, and Fountain, which can be
read without any application at all.
