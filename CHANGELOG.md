# Volpi changelog

Newest version first. The same notes are in the update log on Volpi's Home screen.

## 0.1.1 (Open Beta), 2026-10-09

Faster navigation, steadier PDF pages and charts, safer saving, and updates from Home.

### New in this version

- **Quicker return to files.** Unchanged PDFs, datasets, pictures and papers reuse previously loaded work. Notes and other text files avoid sending their whole contents again when nothing changed.
- **Steadier PDF pages.** Recently used PDF pages and selectable text stay ready for a return visit. Linux page drawing avoids the blank-page problem seen when switching files or resizing the window.
- **Lighter charts and tables.** Chart options reuse prepared data. The Data view keeps its place, shows only nearby editable rows and opens a cell editor when you focus it.
- **Calmer floating controls.** Menus fit the window edges before they appear. Dropdowns, dialogs and sheets open at their full size without the opening fade or scale.
- **Safer edits and imports.** Conflict copies keep continued typing, recovery problems are shown, outside edits stay in history, and Word papers import with their pictures as one change.
- **Lighter research graph.** Graph labels reuse their measured widths when you pan or zoom, instead of measuring the same names every time.
- **Updates from Home.** Home checks for new versions in the background. Use Updated or Update available at the bottom right to check again or install an update and restart.

### What Volpi does

- **Remembered PDF navigation.** Completed PDF navigation, reference text and table locations are kept on this device for later visits. A changed PDF is checked again.
- **Signed updates.** Updates are checked before installation. Choose Update and restart from Home when you are ready. The original 0.1.0 beta needs one manual upgrade.
- **Reusable loaded files.** Recently closed files can reuse their prepared pages, data, pictures or paper bodies within memory limits. First visits and files no longer kept in memory still need loading.

### Known issues

- **Research graph restart.** An occasional return to Home has been reported but not reproduced. If it happens again, include the steps and terminal messages in a bug report.
- **Complex paper layouts.** Oversized blocks and table cells spanning pages still need further checks. Image decoding and export limits also remain under review.
- **Update platform checks.** Linux update packages have been built and signed. Windows and macOS installation and a complete update from an older installed version still need platform testing.
- **First visits still load.** Keeping recently used files reduces repeated work, but very large files and first visits can still take time. There is no complete workspace preload.

## 0.1.0 (Open Beta), 2026-10-07

The first open beta. Read, link, cite and write in plain folders on your computer.

### New in this version

- **A cleaner paper.** Papers no longer mark changes on the page: what you add, change or remove is kept in Versions (the Versions button in the paper's bar). Papers with suggested changes from earlier builds take them in when opened, and the paper as it was stays in its versions. Selected words keep their colour, an equation's formula opens in a small box under it, and the writing hint shows only in an empty paper.
- **More export formats.** Export a paper as OpenDocument (.odt, listed first on Linux, for LibreOffice), Word, PDF, Rich Text, a web page, Markdown, LaTeX or plain text. Numbers, citations and the reference list come out as they read in Volpi; in OpenDocument, equations stay editable.
- **Picture tools.** Open a picture to crop it (in any shape or a fixed one), turn or flip it, make it greyscale, or change its brightness and contrast. Save a copy writes a new picture next to the original. TIFF files from microscopes and scanners open too, and can be saved as PNG.
- **Shortcuts and right-click menus.** Right-click any file or folder (in the sidebar, the library, the shelf, the overview or a pane's name) for its actions; with several files selected, the menu acts on all of them. Ctrl+Tab switches between recent files (hold Ctrl and press Tab again for older ones), Ctrl+Page Up and Page Down go through the files in a folder, and both work in Zen. F2 renames, Ctrl+Shift+M moves, Ctrl+Shift+H shows versions, Ctrl+Alt+S saves a version and F11 turns Zen on and off. The keyboard button in the title bar, or Ctrl+/, lists them all.
- **Word and Excel in search.** Search finds words inside Word documents (including footnotes and comments) and Excel workbooks; a match in a workbook shows its sheet and row.
- **Tidier PDF selection.** Selected text and highlights in a PDF show as one even band per line, without outlines or overlapping boxes. Older highlights are drawn the same way.
- **Night light.** Settings, Night light (also in a PDF's Page view) puts a warm tint over the whole window, with less blue light for reading in the evening. Choose Soft, Warm or Warmer.
- **Zen fills the screen.** Zen mode makes the window full screen and hides everything but the page. Esc, Ctrl+P or the Zen button bring the window back as it was.
- **Recent changes on the overview.** The overview's cards are in a steadier order, and Recent changes shows what changed in each file: added words underlined, removed words struck through. Choose a file to compare it in Versions.
- **Structured papers.** Papers have four heading levels (section to paragraph heading), numbered automatically; a heading called Appendices letters the sections after it A, B, A.1. The Outline in the side panel moves a section up or down with everything inside it, or makes it a level higher or lower, in one Undo step. Insert a table of contents, list of figures or list of tables that stays up to date. Things to check lists broken cross-references, citations missing from the references, uncited references and figures without captions.
- **Zoom, margins and fonts.** Zoom papers with Ctrl+scroll, Ctrl + and − (Ctrl+0 fits), or the zoom menu, and pan by dragging the grey desk. Margins come as presets (Normal, Narrow, Moderate, Wide, Wide sides, Thesis bound, Like LaTeX) or your own values in centimetres. Sixteen academic fonts are included, among them Computer Modern (the LaTeX look), Libertinus, Charis, Source Serif and EB Garamond, plus fonts with the same widths as Times New Roman, Arial, Calibri, Cambria and Georgia. Word exports embed fonts readers may not have.
- **Equations as you write.** In a paper, write $$ E = mc^2 $$ on its own line and press Enter to make a numbered equation, or put the formula between a $$ line and a closing $$ line. $$x$$ inside a sentence becomes inline math. Versions shows equations by their formula and number.
- **Text and reference files.** Plain text files (.txt, .tex, .bib, .ris and similar) open in Volpi and are kept in Versions like notes. A .bib or .ris file can be read as a list of references, added to the reference library, or saved as BibTeX, RIS, CSL JSON or a reference list in any of the six citation styles.
- **A clearer research graph.** Papers join the graph through their links, pictures and the files of their references. Dots and labels keep a readable size at any zoom, labels never overlap, unlinked files sit in a ring around the rest, and drawing is lighter.
- **Versions.** Every change to a branch is kept as an earlier version. Open History, Show versions (or Earlier versions in a file's menu) to see the changes by day, compare any version with the one before it or with now, and bring back one file without touching the others. Notes and papers show added words underlined and removed words struck through; datasets show rows added and removed and values changed; pictures can be swiped. Save a version with a short note to keep how every file looks at that moment.
- **Volpi Ink icons and wordmark.** Volpi's own things (branches, notes, papers, PDFs, datasets, highlights, citations, the graph, Launchpad and reference status) have their own ink-drawn icons, and the name is written in matching lettering with the red seal as the dot of the i.
- **Light and Dark themes.** Besides the warm Day and Night paper, Settings now offers Light (plain white) and Dark (plain black).
- **A calmer Home.** Your branches, Mochi, your profile and this update log each sit in their own box. Mochi's scene follows the time of day: waving in the morning, reading in the afternoon and evening, asleep late at night, camping at weekends, and a bow after two hours of work.
- **Tables in PDFs.** Volpi finds captioned tables in a PDF: hover a table for its chip, or use the Navigate list, to chart it, save it as a CSV file or put it in a note. Two-line headers, merged cells, exponents (2.3 · 10^19) and footnote marks are read correctly, captions caught in a selected area are left out, and a partial selection offers the whole table.
- **Side by side.** Open up to three files next to each other: Ctrl+click a file, drag it onto a pane, or press Ctrl+Enter in Ctrl+P. A link opens next to the file you are writing in, or as a peek you can pin. Highlights can be quoted into the note beside them or cited in the paper beside them. Each branch remembers its panes on this device.
- **Simpler screens.** One bar per document, one save status in the title bar, larger and darker small text, thinner lines, plain solid shadows on buttons, and the same words as the website. Zen mode shows only the page; the files and tools appear when you move to the left or top edge.
- **Saving without interruptions.** Nothing is disabled or reloaded while a save runs. Revert now undoes an editing session instead of the last pause in typing, and history grows much more slowly.
- **Drafts in manual mode.** Switching files or views keeps unsaved edits (with their Undo) instead of asking. The title bar lists them; Volpi only asks when you leave the branch or close the window.
- **Crash recovery and conflicts.** Unsaved edits are kept in a recovery journal and offered back if Volpi closes unexpectedly. A file changed outside Volpi is never overwritten: keep yours, save yours as a copy, or use the disk version.
- **Local profiles.** Each profile is its own workspace with its own branches and settings. Add a password to lock a profile, and complete your profile to sign papers and comments.
- **Reference library with verification.** Check references against Crossref, OpenAlex, arXiv and PubMed. Badges show Verified, Likely, Mismatch, Not found or Retracted, with the reason.
- **Papers recognised on import.** Imported PDFs that look like research papers get their own citation, and the references they cite can be matched and added to the library.
- **Smoother PDF scrolling.** While you scroll, only pages that are still blank are drawn. Selectable text, links, the sharp redraw and previews of nearby pages follow when you stop, and the page field is the only part of the screen that updates as you move.
- **Charts in narrow panes.** When a chart has little room, its options open below it from a button in the toolbar, so the buttons never cover each other.
- **Branch overview.** An overview of recent work, reading progress, files that need attention and reference problems. A branch opens on it, or on the files you had open.
- **Folders and library management.** Nested folders, link-safe move and rename, tags, reading status, stars, saved views, actions on many files at once, quick open (Ctrl+P) and a branch check.

### What Volpi does

- **Research branches.** Every branch is a plain folder on your disk. Import any file type; originals are copied, never changed.
- **Markdown notes and links.** Link notes, PDFs and pictures with <name> or [text](name). The research graph shows how they connect.
- **PDF reader.** Highlights, comments and quotes saved beside the file, links to other files in the branch, and export of an annotated copy.
- **Papers (.vdoc).** Numbered sections, figures, tables and equations, footnotes, cross-references and comments. Export to OpenDocument, Word, PDF and other formats, import from Word.
- **Citations in six styles.** APA, IEEE, MLA, Chicago, Harvard and Vancouver, plus BibTeX, RIS and CSL-JSON export.
- **Search across branches.** Search file names, notes, papers, PDF text, Word and Excel files, and highlights in this branch or every recent branch.
- **Statistics and charts.** Check CSV, TSV and JSON data for problems, chart tables straight from a PDF, and save charts as SVG.
- **Saving, Undo and history.** Changes save on their own, Undo works per editor, and every change to a branch can be reverted or restored.
- **Launchpad.** Pin the files and links you return to most.
- **Licence.** The beta licence agreement is shown once on first start. You can read it again, with the notices for the open-source software Volpi includes, from Home.
- **Look and feel.** Day and night themes, three accent inks, Zen mode, a focus timer and an optional guide. Mochi appears in her own scene on Home.

### Known issues

- **No OCR.** Scanned PDFs without a text layer cannot be searched, quoted, recognised as papers or read for tables.
- **Tables without captions.** Volpi finds a table from its caption. A table without one is not found by itself; select it with the Chart tool.
- **Reference lists are read from the layout.** Unusual layouts can split or merge references. Matching online corrects the details, and nothing is added without your choice.
- **Books and older works.** Books, theses and older papers often show Likely or Not found even when they are real. Use "I checked it myself" for those.
- **Verification is not fact-checking.** A verified reference exists and is described correctly; Volpi cannot tell whether it supports your sentence.
- **Profile passwords are a lock, not encryption.** A password keeps a profile closed in Volpi, but branch folders stay ordinary files on disk. Profiles are not synced between devices.
- **PDF performance on Linux.** Very large or image-heavy PDFs can still stutter on Linux, and a page may stay blank for a moment when you scroll fast.
- **Empty folders.** A new empty folder is remembered by the library but only appears on disk once a file is placed in it.
- **Newer history format.** Branches opened with this build use history format 2, which earlier test builds cannot open.
- **Import and search limits.** Whole-folder import and password-protected PDFs are not supported yet. Search reads the text of Word (.docx) and Excel (.xlsx) files, not older .doc or .xls files. Files over 512 MB cannot be imported.
