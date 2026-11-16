# Research

eDraft comes out of design research: one person working as researcher, designer
and developer, with a group of writers, filmmakers, visual anthropologists and
designers. This page lists what has been published from that work.

## The Writer Never Formats (2026)

**The Writer Never Formats: What belongs in a screenplay editor, and where it
should sit.** Yasir Dorazahi. Design research report, version 1.0,
16 November 2026. 33 pages, 10 figures, 18 tables, 76 references.

- **Read it:** [doi.org/10.5281/zenodo.24285828](https://doi.org/10.5281/zenodo.24285828)
  (PDF on Zenodo)
- **DOI of this version:** `10.5281/zenodo.24285828`
- **DOI of all versions:** `10.5281/zenodo.24285827` — it always leads to the
  newest version

### Abstract

Screenwriting software keeps growing: machine co-writing, storyboards, story
graphs, live shared editing, writing streaks and story-world databases. This
report asks what belongs at the centre of a screenplay editor, what should be
optional, and what should stay out. It presents the design research behind
eDraft, a screenplay editor developed by one person in the roles of researcher,
designer and developer, with a group that grew from three people to 18 writers,
filmmakers, visual anthropologists and designers. They disagreed, and the
analysis uses that disagreement to decide what should be optional. Drawing on
writing research, phenomenology, and visual and media anthropology, it offers
an untested account of why a small obstacle can cost a writer more than its
repair, and reads an editor's keys as a grammar the hand learns. The main theme
in the research notes is that adding functionality does not necessarily improve
the writing experience. From findings in six feature areas the report derives
six design principles, a rule that gives every feature one of four places (on
the page, beside the page, outside the editor, not in the editor) and a status
for every feature (shipped, in test, exploring, kept out). It shows how the
system implements these decisions, and it reports the checks in place so far
(3,856 Swift test functions, 1,263 TypeScript test cases, 221 shared fixture
cases, an accessibility audit) apart from the checks still needed. The group's
size is the author's account; there are no session records or task-based
measures.

### What it covers

1. Introduction
2. Background and related work
3. Attention, the hand and the page — an argument, not a finding
4. Method
5. Findings in six feature areas: machine co-writing and automatic dialogue;
   previsualisation, storyboards and audio references; emotional-arc and
   dialogue-ratio graphs; real-time collaboration; writing streaks, badges and
   word-count celebrations; extensive world-building databases
6. Decisions and their status
7. The system
8. Evaluation: what has been checked, and what still needs checking
9. Discussion

### What it does not claim

- It is a design study, not a controlled experiment. There are no session
  records or task-based measures.
- The size and make-up of the group is the author's account.
- Section 3 is an argument. It has not been tested.
- The app is still being developed, so screens in the report may change.

### How to cite

> Dorazahi, Y. (2026). *The Writer Never Formats: What belongs in a screenplay
> editor, and where it should sit* (Version 1.0) [Design research report].
> Zenodo. https://doi.org/10.5281/zenodo.24285828

```bibtex
@techreport{dorazahi2026writer,
  author      = {Dorazahi, Yasir},
  title       = {The Writer Never Formats: What belongs in a screenplay editor,
                 and where it should sit},
  type        = {Design research report},
  institution = {eDraft},
  address     = {D{\"u}sseldorf, Germany},
  year        = {2026},
  month       = nov,
  note        = {Version 1.0},
  doi         = {10.5281/zenodo.24285828},
  url         = {https://doi.org/10.5281/zenodo.24285828}
}
```

GitHub's **Cite this repository** button gives the same reference (from
[`CITATION.cff`](../CITATION.cff)).

### Licence

The report is licensed under the
[Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
The licence covers the text, tables and diagrams of the report only. It does
not cover the eDraft software or its source code, which are not open source,
the eDraft name and logo, or the screenshots of the apps in Figures 1 and 7.

This is different from the rest of this repository, which stays proprietary
(see [LICENSE](../LICENSE)).

### Comments

Comments on the report, people who want to test eDraft, and research partners
are welcome. Write in
[Discussions](https://github.com/yasirdora/edraft/discussions), or to the email
address on the report's title page.
