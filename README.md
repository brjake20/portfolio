# Portfolio

Personal portfolio site. Closing today, building tomorrow.

A scroll-scrubbed cinematic intro (`portfolio_background.mp4`) followed by receipts, voice, and contact.

## How to preview locally

**Don't** double-click `index.html` — browsers block video playback from `file://` URLs. You need to serve the folder through a local web server. It's a one-line command.

### Option 1 — Python (built into macOS)

Open Terminal (Spotlight → "Terminal"), then run:

```bash
cd ~/Documents/portfolio    # or wherever your folder lives
python3 -m http.server 8000
```

Then visit **http://localhost:8000** in your browser. Press `Ctrl+C` in Terminal to stop the server.

### Option 2 — VS Code Live Server extension

If you have VS Code, install the "Live Server" extension, right-click `index.html`, choose "Open with Live Server."

## Stack

- Static HTML, CSS, JavaScript — no framework, no build step
- Video scrubbing with `requestAnimationFrame` easing
- Hosted on Vercel, source on GitHub

## Live

[yourname.com](https://yourname.com) *(swap in the real URL once deployed)*

## Structure

```
portfolio/
├── index.html                  # The entire site, single file
├── portfolio_background.mp4    # 15s scroll-scrubbed cinematic
├── README.md                   # This file
├── .gitignore                  # Files Git should ignore
└── .gitattributes              # Auto-created by GitHub Desktop, leave it
```

## Contact

- Email: you@email.com
- LinkedIn: [your LinkedIn]
- GitHub: [github.com/brprojects-ctrl](https://github.com/brprojects-ctrl)
