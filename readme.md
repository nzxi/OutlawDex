# OutlawDex
Windows-ready Red Dead Redemption 2 animal lookup. Ships as standalone executables—no Python or extra installs needed.

## Repo Name
- Recommended: `outlaw-dex`

## Download
- Grab the latest release assets from the Releases page:
  - `outlaw-dex-cli-x.y.z-win64.exe` (command-line)
  - `outlaw-dex-tui-x.y.z-win64.exe` (Textual UI)
- Optional: verify integrity with the posted SHA256 checksum.

## What It Does
- Search the full RDR2 animal list by name, region, category, rating, or perfect weapon.
- Two modes in one build: a quick command-line interface and a richer Textual TUI.
- Works completely offline; the bundled `animals.json` data is included.

## Quickstart (Windows)
1) Download the CLI or TUI exe and place it anywhere (no install required).  
2) Run from PowerShell/CMD, or double-click the TUI exe to open the interface.

### CLI examples
```bash
# one-shot search
outlaw-dex-cli-x.y.z-win64.exe --once "wolf region:grizzlies"

# interactive CLI loop
outlaw-dex-cli-x.y.z-win64.exe
```

### TUI tips
- Type in any field and press Enter to search.
- Shortcuts: `Ctrl+S` search, `Ctrl+R` reset, `Ctrl+C` quit.

### Search filters
- Inline: `region:<text>`, `rating:<text>`, `category:<text>`
- Examples: `bear`, `rabbit region:lemoyne`, `elk rating:perfect category:big`

## System Requirements
- Windows 10/11 64-bit.  
- Console access if you prefer the CLI mode.

## Known Notes
- First launch may show a SmartScreen prompt because the exe is unsigned. Choose “More info” → “Run anyway” if you trust the download.
- All data is local; the app never calls external services.

## Support
- Open an issue on the GitHub repo for bugs or feature requests.
- Include the exe version and what you were doing when the issue occurred.
