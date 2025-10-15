# Design principles

These are the rules the work follows. They are written down because they
decide arguments — when a principle and a convenient implementation disagree,
the principle wins.

## 1. The script never leaves the writer's machine

A screenplay is often the only thing a writer owns outright. It should not
have to sit on someone else's server to be edited.

Documents are files on the writer's disk, in formats other software can open.
No account, no sync. This is the premise, not a default — features that would
require breaking it are not built.

## 2. The document is the contract

A file opened and saved without edits comes back unchanged, byte for byte.
An edit to one line changes that line. Anything the application cannot yet
display is still carried through a save rather than dropped.

This is the principle everything else is measured against. It is also the
expensive one: it rules out rewriting a document wholesale on save, which is
how most tools lose the parts they do not model.

## 3. Measure; do not assume

Behaviour that has to match another application's is established by examining
what that application actually produces, not by reasoning about what it
probably does. Where a decision rests on a measurement, the measurement is
recorded alongside it.

## 4. Nothing is lost silently

When something cannot be preserved, the application says so. A loss the writer
is told about is a decision they can make; a loss they discover later is a
defect. Silence is only acceptable when nothing was lost.

## 5. The writer's text is theirs

The application does not rewrite a writer's words to suit its own model. Where
a format forces a choice, the choice is made at the boundary and named, not
applied quietly to the text.

## 6. Production concepts are modelled as concepts

A scene number is an address, not a string typed into a heading. An omitted
scene is a reversible record, not deleted text. Modelling these properly is
what lets them survive editing, reordering and interchange.

## 7. The page is the loudest thing on screen

Interface chrome stays quiet. Colour is used to mean something specific;
anything drawn on the page is keyed to the page rather than to the
application's appearance, so a light page in a dark window still reads
correctly.

## 8. Accessibility is a requirement, not a pass

Anything conveyed by colour, weight or a mark is also available to assistive
technology. A visual treatment that cannot be spoken is incomplete.

## 9. Built by a writer, for writers

Conventions writers rely on are kept. Conventions that exist only because
software has always done it that way are questioned.
