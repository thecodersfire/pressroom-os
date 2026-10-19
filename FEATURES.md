# Built-in features for pressroom-os

Purpose: desktop publishing

1. **prepare a creative project** — run pressroom-os-workspace. It creates ~/Documents/pressroom-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run pressroom-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/pressroom-os-session-plans/.
3. **check project and export readiness** — run pressroom-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/pressroom-os-workspace features/pressroom-os-plan features/pressroom-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for desktop publishing:

1. **GIMP** — org.gimp.GIMP
2. **Krita** — org.kde.krita
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for desktop publishing:

1. **Blender** — create 3D assets and animations (org.blender.Blender)
2. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
3. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
4. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
5. **darktable** — develop RAW photos (org.darktable.Darktable)
6. **VLC** — review media files (org.videolan.VLC)
7. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
8. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
2. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
3. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
4. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
7. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
8. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
9. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
10. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
13. **LibreOffice** (org.libreoffice.LibreOffice) — create reports and spreadsheets.
14. **Zotero** (org.zotero.Zotero) — manage research sources and citations.
15. **Calibre** (com.calibre_ebook.calibre) — organize ebooks and convert documents.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
2. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
3. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
4. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
5. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
6. **Clock** (org.kde.kclock) — set study, work, and routine timers with alarms and a stopwatch.
7. **KBibTeX** (org.kde.kbibtex) — maintain BibTeX citations for research and technical writing.
8. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
9. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
10. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
11. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
12. **Ark** (org.kde.ark) — open and create common project archive files.
13. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
14. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
15. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for desktop publishing. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **PDF Arranger** (com.github.jeromerobert.pdfarranger) — Reorder, rotate, split, and merge PDF pages.
2. **LocalSend** (org.localsend.localsend_app) — Transfer files directly between nearby devices on your local network.
3. **Joplin** (net.cozic.joplin_desktop) — Organize notes and checklists in notebooks.
4. **KBackup** (org.kde.kbackup) — Create user-selected backup archives of files and folders.
5. **Déjà Dup** (org.gnome.DejaDup) — Create user-configured file backups to a chosen destination.
6. **KRename** (org.kde.krename) — Batch rename photo, document, and project files.
7. **Tellico** (org.kde.tellico) — Catalog books, media, games, and other collections.
8. **Skanpage** (org.kde.skanpage) — Scan and arrange multipage documents from a connected scanner.
9. **Merkuro** (org.kde.merkuro) — Organize calendars, contacts, and tasks.
10. **Document Scanner** (org.gnome.SimpleScan) — Scan and save paperwork as image or PDF files.
11. **Contacts** (org.gnome.Contacts) — Keep a local address book.
12. **Calendar** (org.gnome.Calendar) — Plan events, appointments, and work sessions.
13. **Clocks** (org.gnome.clocks) — Use timers, alarms, and world clocks.
14. **Papers** (org.gnome.Papers) — Read and review PDF documents.
15. **KeePassXC** (org.keepassxc.KeePassXC) — Store passwords in an encrypted local vault.
