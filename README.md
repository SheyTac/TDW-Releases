# Thompson Drone Works downloads

Official Windows installers and release notes for Thompson Drone Works. Application source is maintained in a separate private repository. This repository contains download information and compiled release packages.

[Download the latest release](https://github.com/SheyTac/TDW-Releases/releases/latest)

## Install or update

1. Save your work and close all Thompson Drone Works windows.
2. Download the latest `TDW-X.Y.Z-win-x64-setup.exe` from Releases and run it.
3. Open Thompson Drone Works using your desktop or Start menu shortcut.

From v0.3.39 onwards, use **Workspace tools → Check for updates / install update** to see releases and download verified updates. You choose when to install. Updates are not installed automatically in the background.

The EXE is self-contained for Intel/AMD 64-bit Windows; a separate .NET installation is not needed. Distribution is currently unsigned, so Windows may show an unknown-publisher warning. Download only from this repository or your trusted project owner.

The `.update.json` file contains the exact setup filename, version and SHA-256 value. Keep it beside the EXE if using **Choose setup file** or copying the package to another computer. A setup ZIP is provided as a fallback.

## Your records

Saved business records remain on your computer. Setup verifies a local backup before upgrading and keeps the previous app available for rollback. Downloading updates does not send business records to GitHub.

Program files are installed under `C:\ThompsonDroneWorks`. Records remain under `%LOCALAPPDATA%\ThompsonDroneWorks\working`. Keep separate-device backups for protection against disk failure.

Rollback restores the previous application and its pre-update records; work entered after the update stays in a preserved rescue folder. Review your saved work before rolling back.
