# Realm-Creative-Labs
Official Realm Creative Labs portfolio showcasing my software, AI assistants, games, digital tools and creative projects.

# 🚀 Realm Creative Labs

### Software • Artificial Intelligence • Gaming • Digital Innovation

Welcome to **Realm Creative Labs**, an independent development studio creating software, AI-powered tools, games and digital experiences.

This GitHub portfolio showcases our projects, progress and future development.


## 💻 Our Projects

## Realm DVD Creator

**Status: v1.0 Alpha — In Development**

Realm DVD Creator is an offline-first Windows desktop application for preparing DVD-Video projects, calculating disc capacity, designing navigation menus and producing validated DVD-Video output from user-owned, unprotected media.

### Implemented

- PAL DVD-Video conversion, menu authoring, `VIDEO_TS` generation, ISO creation, validation, IMAPI2 burning and finalisation.
- Smart Disc Fit planning with per-title bitrate allocation, capacity checks and multi-movie DVD collections.
- Menu Designer Pro with a resizable three-panel workspace, direct drag/resize editing, editable button text and styling, stock or custom backgrounds, animated backgrounds, safe-area guides, Undo/Redo and preview/test mode.
- Working chapter, audio and subtitle menu generation with automatic pagination and PAL-safe highlight validation.
- Configurable ISO, authored-project and temporary-workspace destinations, disk-space checks, no-overwrite protection and safe application-owned workspace cleanup.
- Local movie, chapter, audio and subtitle inspection using bundled media tools; processing remains offline by default.
- Staged build progress, diagnostics and verification gates that keep Burn unavailable until the authored output and ISO pass validation.
- Genuine aspect-preserving live source preview during encoding, generated-menu preview during authoring, and real FFmpeg timestamp, frame, FPS, speed, stage-progress and ETA telemetry.
- Consent-based update checks and verified local update-package staging; private-repository credentials are not stored in the application.

### Testing status

The v1.0 Alpha development checkpoint passes 105 core regression checks and its self-contained Windows x64 build launches responsively with the expected `1.0.0-alpha` product version. Synthetic-media integration has exercised application startup, media probing, custom and animated menu rendering, chapter/audio/subtitle pagination, PAL button bounds, Smart Disc Fit, multi-movie authoring, `VIDEO_TS`, ISO creation and ISO validation. Menu artwork and edit/preview states shown below were captured from the installed Windows application using synthetic or project-owned assets.

An earlier tested Realm DVD Creator build successfully burned and finalised a physical DVD+R. That disc played in VLC, on a separate standalone DVD player and on a disc-equipped PlayStation 5; PS5 menu and chapter navigation also passed. These are preserved historical hardware-acceptance results, not a claim that every later maintenance build or every player/media combination has been retested. The newer automatic movie-title volume label still requires a fresh physical burn/eject/reinsert check in Windows File Explorer.

The source code remains in a private repository while development and acceptance testing continue. The primary development workspace has moved to a dedicated development drive, while installed software and large DVD output use separate locations. This public repository contains showcase documentation and approved screenshots only; it does not publish source code, user media, diagnostic logs or private paths.

**Public Release Date: TBA — Not Yet Announced**

### Screenshots

| Dashboard | Smart Disc Fit |
| --- | --- |
| ![Realm DVD Creator dashboard](assets/realm-dvd-creator/01-dashboard.png) | ![Smart Disc Fit](assets/realm-dvd-creator/02-smart-disc-fit.png) |

| Multi-movie DVD workflow | Custom menu background |
| --- | --- |
| ![Multi-movie DVD workflow](assets/realm-dvd-creator/03-multi-movie-workflow.png) | ![Menu Designer with custom background](assets/realm-dvd-creator/04-menu-designer-custom-background.png) |

| Drag-and-drop edit mode | Menu preview mode |
| --- | --- |
| ![Menu Designer edit mode](assets/realm-dvd-creator/05-menu-designer-edit-mode.png) | ![Menu Designer preview mode](assets/realm-dvd-creator/06-menu-designer-preview-mode.png) |

| Updates | Build and Verify |
| --- | --- |
| ![Realm DVD Creator updates screen](assets/realm-dvd-creator/07-updates.png) | ![Build and Verify screen](assets/realm-dvd-creator/08-build-verify.png) |

## REALM HUB

### *Your PC. Your Software. Your Realm.*

**Status: v0.2.0 IN DEVELOPMENT**

Realm Hub is a native Windows desktop application designed as the central home for Realm Creative Labs software and live PC health information. It combines a privacy-conscious application launcher, responsive hardware monitoring, desktop widgets, system-tray controls and persistent visual personalisation in one dashboard.

### Current development features

- Combined PC-health dashboard with real CPU, GPU, RAM, VRAM, disk, network and uptime readings where Windows and the hardware expose them.
- Bounded live CPU, GPU, memory, network and disk history graphs with session peaks.
- CPU/GPU temperatures, storage information and fan readings where supported; unavailable sensors are clearly labelled rather than simulated.
- Realm application catalogue with genuine installed-state detection, custom executable locations and launch support.
- Compact, Standard and Advanced desktop-widget layouts backed by the same shared monitoring service.
- Windows system-tray integration, minimise-to-tray behavior and single-instance window restoration.
- Realm Neon, Realm Professional, Realm Cyber, Realm Carbon and Realm Minimal themes.
- Persistent application-tile ordering, favourites, dashboard section visibility and named dashboard layouts.
- Local settings with no account requirement, telemetry or cloud upload by default.
- Built-in Realm PC Suite with guarded Smart Cleaner, read-only Windows diagnostics, genuine installed-driver inventory, reversible startup management, storage reporting and measured network diagnostics.
- Responsive Smart Cleaner with protected locations, cancellation, 250-row virtualised pages, full file review and explicit confirmation before any supported cache file can be removed.
- Theme-aware tables and dialogs with readable headers, rows, selection and long-path inspection in Realm Neon, Realm Carbon and Realm Professional.

### v0.2.0 verified progress

The v0.2.0 private-development checkpoint passed a clean Windows Release build and 24/24 automated acceptance tests. Real isolated desktop acceptance exercised a 20,000-file disposable Smart Cleaner scan, active cancellation, one-click selection, Select All/None, full review, exact deletion of one disposable test file and safe handling of a deliberately locked disposable file. The same acceptance session read genuine Windows driver inventory, ran read-only Windows Update/Event Log diagnostics and refreshed mounted-drive capacity without the previous Storage binding error.

Unsupported CPU temperature, fan and storage-health sensors remain labelled **Not available** when the normal non-elevated provider cannot supply them. Administrator repairs, driver installation, router changes and cleaning of real user files were not performed. ASTRA remains disconnected with zero action authority. The currently installed build has not been replaced by v0.2.0.

Realm Hub remains in active private development. Major dashboard-section reordering, resizable dashboard cards, complete custom-theme management and additional hardware/configuration acceptance tests are still being completed. Its private source code is not published in this showcase.

**Public Release Date: TBA — Not Yet Announced**

### Screenshots

| Combined dashboard | Live PC monitor |
| --- | --- |
| ![Realm Hub combined dashboard](assets/realm-hub/realm-hub-dashboard.png) | ![Realm Hub live PC monitor](assets/realm-hub/realm-hub-pc-monitor.png) |

| Realm application launcher | Desktop widget |
| --- | --- |
| ![Realm Hub application launcher](assets/realm-hub/realm-hub-app-launcher.png) | ![Realm Hub desktop widget](assets/realm-hub/realm-hub-desktop-widget.png) |

| Realm Neon | Realm Professional |
| --- | --- |
| ![Realm Hub Neon theme](assets/realm-hub/realm-hub-neon-theme.png) | ![Realm Hub Professional theme](assets/realm-hub/realm-hub-professional-theme.png) |

![Realm Hub Theme Studio](assets/realm-hub/realm-hub-theme-studio.png)

### Realm Hub v0.2.0 development screenshots

These are real Windows captures from the isolated v0.2.0 acceptance build. Smart Cleaner used only a neutral disposable test folder; the images contain no personal filenames, user-profile paths, settings, credentials or private source. The Storage page was verified separately, but its hardware screenshot is intentionally not published because it contains local drive labels.

| Responsive Smart Cleaner | Full cleanup review |
| --- | --- |
| ![Realm Hub v0.2.0 Smart Cleaner showing readable virtualised results](assets/realm-hub/realm-hub-v020-smart-cleaner.png) | ![Realm Hub v0.2.0 Smart Cleaner review window showing one disposable test file](assets/realm-hub/realm-hub-v020-cleaner-review.png) |

| Safe locked-file result | Genuine Windows driver inventory |
| --- | --- |
| ![Realm Hub v0.2.0 safely skipping a locked disposable test file](assets/realm-hub/realm-hub-v020-locked-result.png) | ![Realm Hub v0.2.0 Driver Centre with readable themed Windows inventory](assets/realm-hub/realm-hub-v020-driver-centre.png) |

## Realm Book Creator — Your Story, Your Voice

**Application: Realm Book Creator**<br>
**Version: v0.1.0**<br>
**Status: PRIVATE DEVELOPMENT**<br>
**Public Release: TBA — Not Yet Announced**

*A helping hand for writers, from the first idea to the finished book.*

Realm Book Creator is an AI-assisted book-writing and publishing application being developed by Realm Creative Labs. It is designed for aspiring authors, independent writers, fantasy authors and anyone who has a story to tell but sometimes struggles to find the next words.

Some writers have amazing ideas but find it difficult to turn them into a manuscript. Others run out of inspiration halfway through a chapter, get stuck developing characters, lose track of their fictional worlds or find editing and formatting overwhelming. Realm Book Creator aims to take some of that pressure away and help writers keep moving forward without taking control of their work.

### Available in v0.1.0

- Create and reopen private local book projects.
- Write, edit, add, remove, reorder and organise chapters.
- Automatically save manuscript progress.
- Track chapter and whole-book word counts and writing targets.
- Use native Windows spellchecking and standard editor undo/redo.
- Review repeated-word, spacing and basic UK/US spelling suggestions.
- Accept or reject each writing suggestion individually.
- Keep basic Story Bible records for characters and locations.
- Export an ordered plain-text manuscript without overwriting an existing export.

The current writing guidance is offline. Version v0.1.0 does **not** include a connected generative AI model and does not send manuscript text to an AI service.

### IN DEVELOPMENT / PLANNED

- AI story brainstorming and idea generation.
- Help overcoming writer's block.
- Suggestions for the next scene, dialogue and plot developments.
- Full book drafting from author-approved outlines.
- Advanced grammar and punctuation checking.
- Rewriting suggestions that preserve the author's voice.
- Fantasy worldbuilding, lore, timelines and character relationships.
- Book-series continuity checking.
- Professional ebook and paperback formatting.
- Amazon KDP manuscript and cover validation.
- Kindle EPUB and print-ready PDF generation.
- Accurate printed page-count checking.
- Amazon book descriptions, keywords, categories and metadata assistance.
- Guided publishing workflows for Amazon and other retailers.
- Future VectorCraft and EffectCraft artwork integration, subject to verified interfaces.

### Supporting writers, not replacing them

**Realm Book Creator is designed to support writers, not replace them.**

When a writer runs out of ideas or gets stuck on a chapter, the long-term goal is to help them find inspiration, explore new directions and finish their stories. The author remains in control of every chapter, correction and publishing decision.

Version v0.1.0 does not provide full AI book generation, direct Kindle publishing, professional EPUB or print-ready PDF output, or automatic retailer submission. Nothing is published automatically.

### Screenshot

![Realm Book Creator v0.1.0 Writing Studio](assets/realm-book-creator/01-writing-studio.png)

## Realm Business Tracker & Realm TCG Stock Manager

**Applications: Realm Business Tracker (Windows) and Realm TCG Stock Manager (Android)**<br>
**Status: PRIVATE DEVELOPMENT — phone-to-PC sync in testing**<br>
**Public Release: TBA — Not Yet Announced**

*One stock list for the shop, on the PC and in the pocket.*

Realm Business Tracker is an offline-first Windows desktop app for a small trading-card business: products, stock, sales, expenses and profit reports in one local database. Its companion, Realm TCG Stock Manager, runs on an Android phone for scanning, selling and checking stock away from the desk. The aim is for both to share one catalogue, permanent barcodes and a single stock ledger.

### Current development features

- Local-only Wi-Fi sync between the phone and the PC: no cloud account, no subscription, nothing leaves the home network.
- Secure pairing with an 8-digit one-time code, plus a certificate-fingerprint check on both screens before the phone trusts the PC.
- Every record has a permanent ID, so repeating a sync can never duplicate a sale or add stock twice.
- Stock is a ledger of changes rather than overwritten totals, and anything uncertain is flagged for review instead of silently overwriting newer records.
- A separate, clearly labelled test copy of the Windows app that refuses to start unless it is confirmed to be using a fake-data test database.

### Testing status

The Windows build passes its automated checks on GitHub (28 core and 9 application tests), and the Android build passes its checks and an emulator run. A home Wi-Fi test with fake products on a real PC and phone paired successfully; a phone sale reached the PC exactly once, and stock added on the PC reached the phone. Sales made on the PC do not yet change stock on the phone, and remote access and TikTok Shop integration have not been started. The live business database was not touched by any test, and real stock has not been entered. Source code remains in private repositories.

### Screenshot

Windows test copy showing clearly labelled fake test products only:

![Realm Business Tracker test copy showing fake products](assets/realm-business-tracker/01-windows-products.png)

### 🎮 Willowbrook Games
**Status: In Development**

Our game development projects, including the Willow Brook game world, focused on creating engaging interactive experiences.

### 🤖 ASTRA AI
**Status: In Development**

Our personal AI assistant project, designed to support intelligent automation, software development and connected digital workflows.

### 🛠️ Discord Bot
**Status: Private Development**

A custom Discord bot project, with further information to be shared as development progresses.

## Realm software: latest development work

All of these are in development / alpha. None has been released. The work below has passed automated build checks only; it has not been tested on real devices or hardware.

- **Realm Business Tracker** (Windows) and **Realm TCG Stock Manager** (Android): stock apps for a small trading-card business. New work adds permanent RTCGC barcodes and phone-PC sync with a resolve button for conflicts.
- **Realm DVD Creator** (Windows): in alpha (v1.0.2-alpha line, not released). Now on its main branch: Blu-ray and 4K smart disc fit, ISO verification and a source pre-check.
- **Realm Hub** (Windows): in development (v0.2.0 private checkpoint, not a public release). Now on its main branch: PC Monitor, dashboard layouts, a Realm apps strip and early PC Suite tools.
- **Realm Control Tower** (Windows): v0.1.2-alpha, in development. Now on its main branch: application discovery and management, release readiness, issue tracking, a backup warning, a Software Updates screen and an unsigned test installer built by the automated checks. Still alpha: only automated build checks so far, not tested on real devices, not released, and the installer is unsigned and not yet downloadable.

## 🧪 Development Updates

Projects featured here may still be experimental, under development or undergoing testing.

Public showcases do not necessarily include downloadable applications or publicly available source code.

## 🔐 Source Code and Availability

Some Realm Creative Labs projects are maintained in private repositories.

Public project information, screenshots and release announcements will be shared when ready.

## 🌐 Follow Our Progress

Follow this GitHub profile for future project updates, screenshots and development milestones.

**© 2026 Realm Creative Labs**

*Building the future, one project at a time.*
