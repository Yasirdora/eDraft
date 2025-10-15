# Product overview

## The problem

A screenplay is not only a piece of writing. Once a production starts, it is a
shared document with addresses in it: scene numbers a schedule cites, page
numbers a call sheet turns to, revision colours that tell a crew what changed
since yesterday. Those addresses are what the rest of the department works
from.

Most writing tools treat a screenplay file as text with formatting. When such
a tool opens a document it does not fully understand, the parts it cannot
model tend to disappear on the next save — quietly, and usually without
telling anyone. The writer is not the one who finds out.

## The approach

eDraft treats the document as the contract.

When it opens a file it did not create, it keeps everything that file carries,
including the parts it has no interface for yet. Saving a document without
editing it returns the original bytes. Editing one line rewrites that line and
leaves the rest of the file alone.

That constraint shapes the rest of the product. It rules out convenient
shortcuts — re-serialising a whole document on every save, for instance — and
it means new features have to be built so that the things they do not know
about still survive them.

## Who it is for

Screenwriters who work with other people: writers on a production, writers
sending drafts to people using different software, and writers who want their
work to stay on their own machine.

It is not aimed at collaborative real-time editing, and it is not a
general-purpose word processor.

## What it works with

- **Fountain**, as a plain-text writing format.
- **Final Draft documents**, read and written with the production data they
  carry preserved.
- **PDF**, for sharing and for reading back a script eDraft produced.
- **Word-processor and plain-text sources**, for bringing existing material in.

Interchange is treated as a first-class requirement rather than an export
menu. A script that passes back and forth between eDraft and other software
should arrive intact in both directions.

## Who built it

A working screenwriter who also researches interface design. The decisions
come from doing the work, not from a feature comparison.
