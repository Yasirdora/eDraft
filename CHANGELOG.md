# Changelog

Notable changes to eDraft are recorded in this file, in the shape described by
[Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/). eDraft is one App Store
download for iPhone, iPad and Mac, free (preview); each release says which devices it
reached.
No release so far has supported Word (`.docx`) files; support is planned.

## 2.2 - 2026-11-14 (iPhone, iPad and Mac)

Version 2.2 brings eDraft to iPad and gives every scene in the Navigator a menu
of its own.

### Added

- **iPad.** eDraft runs on iPad, in portrait and landscape. The library uses the
  full width of the screen.
- **A menu for every scene.** In the Navigator, touch and hold a scene (iPhone
  and iPad), or hold the pointer over it and click More (…) or Control-click it
  (Mac). Select, copy, duplicate or delete the scene, or add a note to it. In a
  Final Draft script you can also omit a scene there and restore it; a Final
  Draft script with scene numbers has Omit Scene in place of Delete Scene.
- **Scene details.** Details, in the same menu, shows a scene's length, running
  time, word count, characters and notes.
- **Ideas badge.** On iPhone and iPad, a badge on the Ideas button counts the
  ideas for the open script that you have not opened yet. On the Mac, while the
  Ideas panel is closed, the Ideas button in the toolbar shows a badge when the
  open script has an idea you have not opened yet.
- **iPhone and iPad:** while you read a script, tap the microphone at the bottom
  right to record an idea. It is filed for that script and for the scene at the
  top of the screen.
- **Mac:** the scene commands are also there when you Control-click a scene
  heading on the page.

### Changed

- In Settings, under Notes, you choose the colour of your notes from a menu that
  shows each colour with its name.
- Note colours: Blue has a new shade. On the Dark Page, Purple, Pink, Indigo and
  Cyan have new shades too.
- **iPhone and iPad:** while you read a script, the Ideas button is at the top,
  beside the Navigator button, and the page runs to the bottom edge of the
  screen.
- **iPhone and iPad:** Omit, Restore, Duplicate and Delete are one step each for
  Undo.
- **iPhone and iPad:** in the library, the More menu has one row to switch
  between the list and the gallery. In a script, the More menu no longer has
  Reading Mode; to stop writing, tap the checkmark, as before.
- **Mac:** the Navigator has a new header. The name of the list is at the top,
  with the Script Info button and the filter beside it, and the search field is
  always shown. Script Info shows the script's pages, running time and words;
  the line at the bottom counts its scenes and locations. The Search and Filter
  buttons are no longer in the toolbar, and the scissors button is gone.
- **Mac:** the current scene in the Navigator is marked with a grey bar, and its
  text keeps its colour.
- **Mac:** when you show or hide Ideas and the screen has room, the window grows
  or shrinks by the width of the panel, and the page keeps its size.

### Fixed

- **Mac:** giving a new label to a note you had not written in yet could remove
  the note. The note now stays and gets its label.
- **Mac:** for a recording in which no words were found, Action and Dialogue stay
  dimmed.

## 2.1 - 2026-11-10 (iPhone and Mac)

Version 2.1 gives each person's notes their own colour, adds labels, and works
better with VoiceOver and Voice Control.

### Added

- **One colour per person.** In a script, everyone whose notes carry their name
  keeps one colour of their own: on the page, in the notes sheet (iPhone) or on
  the note card (Mac), and in the Navigator. Choose your colour in Settings >
  Notes, or leave it on Automatic. A colour you choose is for that device.
- **Labels.** Give a note a label of your own, such as "Rewrite". In the
  Navigator's Notes list, tap or click a name or a label to see only the
  matching notes.
- **German times of day.** Once you use TAG, NACHT, MORGEN, ABEND or DÄMMERUNG
  in an INT. or EXT. heading, the suggestions offer them on your other INT. and
  EXT. headings too.
- **Mac:** Focus keeps a whole scene bright while the cursor is in its scene
  heading, and a whole speech bright while it is in a character name,
  parenthetical or dialogue.
- **Mac:** you can change your name and role in eDraft > Settings… > Notes.

### Changed

- An eDraft note keeps its colour and label in eDraft, Fountain and Final Draft
  files. In a Final Draft file, a colour Final Draft itself set on a note is
  kept, and shown as a small square.
- When eDraft saves or exports a Final Draft file, another person's note keeps
  their name. Your name is no longer written in front of theirs.
- The title page keeps the title as you type it, in its Title field and in your
  files. PDF and print still show it in capitals. Changes to the title page of a
  Final Draft file are saved into that file, in its own style.
- A German time of day before CONTINUOUS counts as the heading's time of day.
- When the kind of line changes as you type, VoiceOver says the new kind, such
  as Action or Character. For a note mark, it says whose note it is.
- **iPhone:** with VoiceOver, a scene row in the Navigator is one item, and a
  double tap opens the scene. For Voice Control, more buttons and rows go by the
  words shown on them.
- **Mac:** note marks are small round dots in the left margin, and they are
  easier to click. The note card grows with its notes, up to a set height.
- Ideas: when no words are found in a recording, it shows "No words found", and
  you can still place it as a note.

### Fixed

- Renaming a character keeps your cursor where it was.
- **iPhone:** ideas that arrive through iCloud appear while eDraft is open.
- **iPhone:** a script deleted from iCloud Drive in the Files app, outside
  eDraft, disappears from your library by itself.

## 2.0 - 2026-11-04 (iPhone and Mac)

Version 2.0 adds German and Ideas.

### Added

- **Ideas.** On iPhone, tap the microphone in the library and say what is on
  your mind. eDraft saves the recording first; then, if your iPhone has a speech
  model for your language, it writes down the words. Place the idea in your script as a note, action, dialogue or
  new scene — on your iPhone, or on your Mac (View > Ideas) through your own
  iCloud. Or ask Siri: "Add an idea in eDraft".
- **German.** When your iPhone or Mac is set to German, menus, windows and messages are in
  German. INNEN. and AUSSEN. start a scene heading, and the writing suggestions
  offer them. On iPhone you can dictate a heading: "innen Küche, Tag".
- **Notes on a single word.** Select a word or phrase and add a note. It sits on
  those words with a soft tint, stays on them as you write, and is kept in eDraft,
  Fountain and Final Draft files.
- **Page Words.** An eDraft script can print (MEHR) and (FORTS.) instead of
  (MORE) and (CONT'D), in the PDF and in print.
- **iPhone:** a new library — New Screenplay and Open… at the top, search at the
  bottom; Open… takes a script, a PDF or a photo; press and hold a script to
  share, duplicate, rename or delete it.
- **iPhone:** Use Light Page — in Dark Mode, the ⋯ menu turns the script page
  white while the rest of eDraft stays dark.
- **iPhone:** Act Break in the element menu, as on the Mac.
- **Mac:** Format > Font with Bold (⌘B), Italic (⌘I) and Underline (⌘U).
- **Mac:** the welcome window shows the first page of each script.

### Changed

- Undo brings back a deleted note, and changes to the title page can be undone.
- A new installation in Germany, Austria, Switzerland, Liechtenstein or
  Luxembourg starts on A4.
- **iPhone:** importing a PDF or a scan keeps numbered scene headings and drops
  CONTINUED lines.
- **iPhone:** printed and exported PDFs carry revision marks, together with bold,
  italic, underline, strikethrough and highlights.
- **Mac:** the page view shows what the PDF prints — (MORE), (CONT'D), CONTINUED,
  scene numbers and page numbers, where they print.
- Revision colours follow the industry order: after Goldenrod come Buff, Salmon
  and Cherry.

### Fixed

- Scripts with more than three rounds of revisions open correctly.
- (OFF) and (FORTS.) are recognised as character extensions, so JONAS (OFF) is
  the character JONAS.
- **Mac:** VoiceOver names the switches in the Revisions popover and the
  screenplay editor itself.

## 1.1 - 2026-10-18 (iPhone), 2026-10-19 (Mac)

### Added

- **Mac:** revisions in Final Draft (`.fdx`) scripts — the
  revisions recorded in a script, each changed line marked in the margin;
  Revision Mode marks your own edits in the current revision; click a revision
  mark to see exactly what changed; Production > Clear Revised removes the marks
  when you lock a draft.
- **Mac:** locked pages keep their page numbers, such as 1A and 2–3, on screen
  and in print.

### Fixed

- FADE IN: appears at the left margin, following screenplay convention.
- **Mac:** act breaks are read and saved correctly.

## 1.0 - 2026-10 (iPhone)

The first iPhone release, added to the same App Store purchase as the Mac app.

### Added

- Screenplay writing on iPhone: elements formatted as you type, chosen from the
  bar above the script; bold, italic, underline, strikethrough and highlights;
  reading and writing with one tap.
- The Navigator for scenes, cast and notes; notes on any passage; a title page.
- Revisions: mark a draft when you send the script out; an asterisk then marks
  each changed line.
- Open Final Draft, Fountain and eDraft files from Files, Mail, Messages or
  AirDrop, and keep them in their own format.
- Scan paper pages, or import a PDF or a photo, to turn them into a screenplay
  you can edit.
- Export an eDraft file, PDF, Final Draft, Fountain, rich text or plain text, or
  print.

## 1.0.1 - 2026-10-13 (Mac)

### Changed

- Find opens under the toolbar, and a match above the window scrolls into view.
- The text style bar is clearer, with new highlighter and Add Note icons.

### Fixed

- Layout and Export have VoiceOver labels.

## 1.0.0 - 2026-10 (Mac)

The first public release, on the App Store for macOS 26 and later.

### Added

- Screenplay editing with element formatting as it is typed: scene headings,
  action, character cues, dialogue, parentheticals and transitions.
- Tab and Return move between screenplay elements; character names are
  suggested as you type; find and print.
- Final Draft document and Fountain import and export, in both directions.
- PDF and plain-text export.
- Import from plain text, with every unsure line reported before the import
  commits and the writer's override taken as final.
- A title page, a Cast tab, and a scene navigator built from the script.
- Revisions in eDraft scripts: mark a draft when you send your script out; from
  then on, an asterisk marks each line whose text has changed. Export a PDF with
  the asterisks, or one without them.

Revision colours, locked pages and scene numbering commands were not part of
1.0.0. Revisions in Final Draft files came with 1.1.
