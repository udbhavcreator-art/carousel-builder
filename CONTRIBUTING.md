# Contributing to Carousel Builder

## Codebase Structure

Everything lives in a single file: `index.html`.

The JavaScript is divided into clearly labelled sections:

| Section | What it does |
|---|---|
| `STATE` | Global variables — slideCount, currentTheme, customAccentColor, slides[], bgImages{} |
| `THEMES` | The `THEMES` object — 6 colour + typography definitions |
| `RENDER` | html2canvas rendering pipeline — builds each 1080×1080 slide |
| `DOWNLOAD` | Sequential PNG download and ZIP + caption.txt export via JSZip |

## Ideas for Contributions

- New themes (new colour + font combos in the `THEMES` object)
- New slide layouts (e.g. quote card, stat card, image-full)
- Figma export (generate `.fig` or design tokens)
- Instagram API upload integration
- More font options via Google Fonts
- Dark / light app-UI toggle (separate from slide themes)
- Slide reorder via drag-and-drop
- Undo / redo history

## How to Test

1. Open `index.html` directly in Chrome (no build step, no server needed)
2. Make changes, refresh the page, verify visually
3. Test PNG download and ZIP download across all 6 themes
