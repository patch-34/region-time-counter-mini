# Patch34: Region Time Counter Mini

Scripts and tools for REAPER. Useful, weird, and everything in between.

---

Minimal floating window that displays the total unique length of all regions in HH:MM:SS. Overlapping regions are merged — no double-counting.

No dependencies. No js_ReaScriptAPI, no SWS required.

## Installation

1. In REAPER: **Actions → Show action list…**
2. Click **ReaScript: Load…**
3. Select `Patch34_Region_Time_Counter_Mini.lua`
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

## License

MIT
