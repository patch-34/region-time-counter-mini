# Region Time Counter Mini

**English** · [Русский](README_RU.md)


Minimal floating window that displays the total unique length of all regions in HH:MM:SS. Overlapping regions are merged — no double-counting.

No dependencies. No js_ReaScriptAPI, no SWS required.

## Installation

### ReaPack

Import the [Patch34 ReaPack catalog](https://raw.githubusercontent.com/patch-34/patch34-reapack/main/index.xml) via **Extensions → ReaPack → Import repositories…**. Locate **Region Time Counter Mini** under **Browse packages**, install and synchronize it.

### Manual installation

1. In REAPER: **Actions → Show action list…**
2. Click **ReaScript: Load…**
3. Select `Region_Time_Counter_Mini.lua`
4. Optionally assign a keyboard shortcut or add to toolbar

## Features

- Total unique region time (union of all regions)
- Correct overlap handling
- HH:MM:SS display
- Fixed window width — no UI jumping
- Auto-refreshes while open
- Close with the window button or Esc

## Notes

The window titlebar is intentionally empty to avoid macOS minimum width constraints. The title is drawn inside the UI instead.

## License and credits

Distributed under the [MIT License](LICENSE).

Author: [Aleksei Vorobev / Patch34](https://github.com/patch-34).