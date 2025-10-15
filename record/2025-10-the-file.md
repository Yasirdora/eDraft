# The file

## The problem

A screenplay file carries data beyond the page: scene numbers, revision marks,
notes, omissions. Applications that do not model it drop it on save. The loss
is silent, and it is found by whoever reads the file next.

Word processors are built for prose and restyle a document on their own terms.
Screenwriting applications know the form, which is not the same as care with
the file. Phone writing is where both fail most.

## Established

- **The document is the contract.** Opened and saved without edits, a file
  returns the original bytes. A one-line edit changes that line and nothing
  else, including data the application cannot yet display.
- **The application serves the format.** A forced choice is made at the
  boundary and named, never applied quietly to the writer's text.
- **Measure, do not assume.** Behaviour that must match another application's
  is established by examining its output, not by reasoning about it.
- **Nothing is lost silently.** A loss the writer is told about is a decision
  they can make. A loss they find later is a defect.

## Ruled out

- A Markdown editor. Fountain is an open text export, not the premise.
- A service. No account and no eDraft server holding a script. A
  script that lives on more than one device does so through iCloud Drive, which
  is Apple's and is optional.
- An invented format, first. Interchange comes before invention.

## Open

How a screenplay is modelled in memory, how pagination is decided, and how a
save preserves what the model cannot express.
