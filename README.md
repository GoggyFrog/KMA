# KMA Startup Manager

**Version:** 2.1.0

## Overview

KMA Startup Manager is a Windows utility for scanning and managing startup programs and entries. The application detects startup items in the Windows Registry, Startup folders, and Scheduled Tasks, displays them in a simple graphical interface, and allows removal of unnecessary entries.

The project is intended for system administrators and advanced users who need a quick way to analyze and control Windows startup behavior.

---

## Release format

This repository contains **binary release files only** (no source code publication in this repo):

- `KMA.exe`
- `latest.json` (manifest for in-app auto-update)

---

## Features

* Scan startup entries from:

  * Windows Registry
  * Startup folders
  * Scheduled Tasks
* Display startup items in a structured table
* Show detailed information for each entry
* Open file location in Windows Explorer
* Remove unwanted startup entries (administrator privileges may be required)

---

## Quick start

1. Download `KMA.exe` from the GitHub release page (or repository file list).
2. Run the file by double-clicking it.
3. For full functionality, allow administrator privileges when prompted by Windows (UAC).

---

## Security notice

* The application accesses Windows Registry and system startup locations.
* Removing startup entries modifies system configuration — use with caution.
* It is strongly recommended to create a system restore point or registry backup before making changes.
* Windows SmartScreen or antivirus software may warn about the executable due to its system-level access. Add the file to exclusions if necessary.

---

## Known limitations

* Windows only.

---

## Author

* GitHub: [https://github.com/GoggyFrog](https://github.com/GoggyFrog)
* Telegram: [https://t.me/kma_tools](https://t.me/kma_tools)
