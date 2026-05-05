# Carousel Builder — Free & Open Source

A free, local, single-file tool to create Instagram carousels. No account, no server, no data leaves your device.

## Features

- Variable slide count (1–20 slides)
- 6 built-in themes
- Custom accent colour picker
- Background image upload per slide
- Text alignment & font size controls
- Sequential PNG download
- ZIP download with caption.txt
- Built-in Claude prompt guide

## How to Use

1. Download `index.html`
2. Open it in Chrome
3. Done — no install, no server, no sign-up


## User Workflow

The tool has a simple 6-step left panel. Work top to bottom and watch the live preview update on the right.

**Step 1 — How many slides?**
Pick a number from 1 to 20 using the +/- buttons. The slide editor below will expand or collapse to match.

**Step 2 — Paste Content**
Paste your carousel text in the format the tool expects (one slide per block). Hit **Parse** and the tool splits your content into individual slides automatically. Use the built-in **Prompt Guide** (top-right button) to get the exact format to feed into Claude.

**Step 3 — Theme**
Choose one of the 6 pre-built themes. Use the colour picker to override the accent colour if you want a custom brand colour.

**Step 4 — Edit Slides**
Click any slide row to expand it. You can:
- Edit the heading and body text directly
- Change text alignment (left / centre / right)
- Adjust font size
- Upload a background image for that slide

**Step 5 — Caption**
Write or paste your Instagram caption. When you ZIP download, a caption.txt is included automatically.

**Step 6 — Download**
- **Download All** — exports each slide as a numbered PNG sequentially (01.png, 02.png …)
- **ZIP** — packages all PNGs + caption.txt into a single zip file ready to upload

## How to Contribute

1. Fork this repo
2. Make your changes
3. Submit a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Tech Stack

- Vanilla HTML / CSS / JS
- [html2canvas](https://html2canvas.hertzen.com/)
- [JSZip](https://stuk.github.io/jszip/)
- Google Fonts

## License

MIT — see [LICENSE](LICENSE)

