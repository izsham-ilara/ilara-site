# Ilara — Landing Page

The decision layer for live mobile games. Your dashboards tell you what happened; Ilara tells you what to do next.

This is a self-contained static landing page (`index.html`) — no build step, no dependencies. Fonts load from Google Fonts; everything else is inline or in `assets/`.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

- `index.html` — the full page (HTML + inline CSS/JS)
- `assets/` — logo, favicon, and image
- `.nojekyll` — serve as-is on GitHub Pages (no Jekyll processing)

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Railway). For GitHub Pages: Settings → Pages → deploy from `main` / root.
