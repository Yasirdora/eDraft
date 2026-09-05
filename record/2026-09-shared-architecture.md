# Shared architecture

## Two implementations, one behaviour

The Apple applications run a second implementation of the engine, in Swift.
Two implementations of a rule drift, so the TypeScript engine is authoritative:
it generates a corpus of cases — parse, serialise, paginate — and the Swift
engine replays every one. A rule that behaves differently on one side fails
there rather than in a writer's hands.

## One product, two surfaces

The Mac application could not be a second codebase that happened to open the
same files. The code with no framework in it — the editor model, the edit
planner, the casing memory, the document model — moved into a package both
platforms link, and the panels that were already plain SwiftUI moved with it.
What stayed per-platform is what genuinely differs: the text system, the
chrome, the input.

## Enforced, not agreed

The boundary is checked in the build. The shared package may not import a UI
framework, and a screenwriting rule may not be decided in a view. A rule that
lives in a view is a second editor, and the two applications will disagree.

## Open

The engine and the surfaces existed. The application had not shipped.
