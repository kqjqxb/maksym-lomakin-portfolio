# Maksym Lomakin – Portfolio

Single-page portfolio: senior React Native engineering, the Peacera app, and AI-agentic development.

Live: https://kqjqxb.github.io/maksym-lomakin-portfolio/

## Structure

- `index.html` – the whole page (inline CSS/JS, no build step)
- `assets/` – photo, Peacera screenshots and icon, DevLog screenshot, App Store badge
- `favicon.svg`

## Editing

- **LinkedIn posts** – add entries to `POSTS` near the bottom of `index.html`
  (`{ date, title, text, url }`). The posts grid stays hidden while the array is empty.
- **Terminal replay** – lines live in `LINES` in the same script.
- **Photo** – replace `assets/maksym.png` (square, 600px+ looks sharpest).

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages → Settings → Pages → Deploy from branch → `main` / root.
