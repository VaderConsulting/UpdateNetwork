# UpdateNetwork

VB6 Update Network utility (`UpdateNetwork.exe`) that broadcasts `WM_SETTINGCHANGE` for `Environment` via `SendMessageTimeout` so apps refresh environment/network settings, then exits. Open `UpdateNetwork.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `UpdateNetwork` (`UpdateNetwork.vbp`) | VB6 | WinForms exe | Broadcast environment setting-change to all windows |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `UpdateNetwork.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/UpdateNetwork`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
