# Interchange

## The engine as a package

The screenwriting engine was separated from the application that uses it: no
framework, and no dependency beyond the platform. Parsing, pagination,
prediction, choreography, numbering and export live there, and nothing above
it decides a screenplay rule.

## In

Word documents, plain text and paste, read without a third-party reader. Every
line the classifier is unsure of is reported with the reason before the import
commits, and the writer's override is final.

## Out

Word and PDF, alongside Final Draft and Fountain. A PDF the application
produces carries its own source inside the file, so reopening one restores the
script rather than re-deriving it from the page.

## What the round trips exposed

Every format had to be proved in both directions, and the proof found the
faults: a page-break paragraph carrying no text, so the break was dropped on
import; a multi-line passage collapsing into one line; a tab in the middle of
a line changing the text quietly.

## Open

The engine and the page were one platform's. The next phase took both to iOS
and macOS.
