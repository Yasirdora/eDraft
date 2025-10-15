<p align="center">
  <img src="media/logo.svg" width="120" alt="eDraft Logo">
</p>

# eDraft

> *This repository contains documentation, examples, and images. The application source code is private for now.*

The journey started with a blank page.

For a writer, a script can be years of work, thought, and imagination captured in one document. It can hold unpublished ideas, personal notes, and confidential production material long before anyone else is meant to see it. 

**That should remain under the writer's control.**

Writing software should not require a writer to upload their script, store it on someone else's servers, or hand it to a third party simply to write, open, or save it. 

The same principle applies to the file itself: **eDraft** reads and writes the formats used in screenwriting and production, preserving what those files carry — *including information it cannot yet display*.

Made by a writer, for the writers.  
**No account, no sync, and no connection required to write, open, or save.**

---

## Why eDraft exists

**Writing is personal before it is collaborative.** 

A draft often begins with one person thinking, rewriting, cutting, reconsidering, trying and retrying. That process needs time and concentration. It should *not* require a shared workspace, an online account, or a permanent connection.

eDraft does not require you to upload your script or store it on someone else's server. You open a file, work on it locally, and save it back to your disk for collaboration, when you want it.

### Built for writing

Screenwriting has its own language: *Scene headings. Action. Character cues. Dialogue. Parentheticals. Transitions.*

eDraft understands that language. As you write, it handles the structure and formatting without turning the process into menus, modes, and commands. 

> **Writing the story is the craft. Using the software shouldn't be.**

---

## The file matters too

A screenplay is not only what appears on the page. In production, the file may also carry *scene numbers, revision information, notes, omitted scenes,* and other data used by different departments.

eDraft is designed to preserve what a file contains, including information it cannot yet display.

---

## What it does

- **Writing:** A screenplay editor built around the elements writers expect: scene headings, action, character cues, dialogue, parentheticals, and transitions.
- **Local files:** Scripts remain ordinary files on your machine. No account, required sync, or permanent internet connection.
- **Interchange:** Reads and writes formats used in screenwriting and production workflows, including Final Draft documents and Fountain, with import from common text and word-processing sources.
- **File preservation:** A supported file opened and saved without edits can be preserved *byte for byte*.
- **Notes:** Notes remain attached to the text they refer to and survive a round trip through supported software.
- **Production features:** Scene numbering, revisions, and omitted scenes are represented as production data rather than visual decoration.

---

## Example

The [`examples/`](examples) directory contains a short original scene in two formats:

- `demo-scene.fdx` — Final Draft format, including a note and an omitted scene.
- `demo-scene.fountain` — The same scene in Fountain. Fountain has no equivalent representation for an omitted scene, so scene 2 is absent while the numbering retains the gap.

To test the FDX round trip, take the file's checksum:

```sh
shasum -a 256 demo-scene.fdx
```

Open the file in eDraft, save it without making changes, and run the command again. The checksums should match.

---

## Status

eDraft is in **active development** and is not yet publicly released.

- **In development:** macOS, iPadOS, iOS, Web, and a Chrome extension
- **Planned:** Windows, Linux, and Android

See the [roadmap](docs/roadmap.md) for current and planned work.

---

## Documentation

- [**Product overview**](docs/product-overview.md) — What eDraft is and who it is for
- [**Design principles**](docs/design-principles.md) — The principles behind the product
- [**Roadmap**](docs/roadmap.md) — Current and planned work
- [**FAQ**](docs/faq.md) — Common questions

---

## Collaboration

eDraft is open to collaboration with screenwriting professionals, educators, researchers, and developers. 

*Research licences are available on request.*

**Contact:** [edraft@ysr.design](mailto:edraft@ysr.design)

---

<p align="center">
  <i>Made by a writer, for the writers.</i><br>
  Source code, research, and internal design documents are private.<br><br>
  &copy; 2025 Yasir Dora. All rights reserved.
</p>