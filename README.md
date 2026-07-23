# ScheduleBrief Viewer Releases

Official public binary releases for ScheduleBrief Viewer by Fredericksburg Foundry LLC.

This repository contains published installers, checksums, and release notes only. The proprietary ScheduleBrief source code is maintained in a private repository and is not distributed here.

## Current release

The current test build is [ScheduleBrief Viewer v0.2.0-alpha](https://github.com/FXBGFoundry/schedulebrief-releases/releases/tag/v0.2.0-alpha).

Download:

- `ScheduleBrief-Viewer-Setup-v0.2.0-alpha.msi`
- `ScheduleBrief-Viewer-Setup-v0.2.0-alpha.msi.sha256`

Verify the MSI's SHA-256 checksum before installing. This alpha is unsigned, so Windows may display an Unknown Publisher or SmartScreen warning. Do not bypass organizational security policy.

## Installation

The MSI upgrades v0.1 and installs for the current Windows user without administrator elevation:

- Application folder: `%LOCALAPPDATA%\ScheduleBrief`
- Executable: `%LOCALAPPDATA%\ScheduleBrief\ScheduleBrief.App.exe`
- Shortcuts: desktop and Start menu
- Uninstall: Windows Settings > Apps > Installed apps > ScheduleBrief Viewer

The installer is self-contained for Windows x64. It does not require Microsoft Project, Primavera, Microsoft Office, or a separately installed .NET runtime.

## What ScheduleBrief Viewer does

ScheduleBrief Viewer is a free, read-only Windows schedule viewer. It provides:

- Project summary information
- A hierarchical task table
- A synchronized Gantt timeline
- Task details
- Search with hierarchy context
- Timeline zoom and Fit Project
- A unified Gantt print window with page preview, zoom, navigation, and installed-printer selection
- Local PDF export of the current filtered and expanded Gantt view
- Local drag-and-drop and file opening

It attempts Microsoft Project `.mpp`, `.mpt`, MSPDI `.xml`, `.mpx`, Primavera P6 `.xer` and `.pmxml`, and SDEF `.sdef` files through MPXJ.Net 16.1.0. Format compatibility varies; use authorized test schedules and report parser-specific issues without attaching sensitive schedule data publicly.

## Local and offline privacy

ScheduleBrief Viewer operates locally. It does not upload schedule files, modify source schedules, use cloud APIs, create accounts, or include telemetry. Printing and PDF export happen only after an explicit user command.

## Alpha limitations

This is an early test build. MPP/MPT, XER, PMXML, SDEF, and MPX require broader compatibility testing with authorized samples. Physical-printer compatibility depends on the installed Windows driver. The paid Briefing edition, schedule editing, schedule-health analysis, licensing, updates, accounts, and cloud features are not implemented.

## Proprietary notice

ScheduleBrief application code and product assets are proprietary. No source-code license is granted by this public distribution repository. Third-party license notices are bundled inside the installer.

Copyright © 2026 Fredericksburg Foundry LLC. All rights reserved.
