# ESTO ARKIS — 1 BHK landing page

Static site. No build step, no dependencies to install.

## Contents
- `index.html` — the page
- `support.js` — runtime required by `index.html`
- `assets/` — logo
- `uploads/` — renders and imagery used by hero + gallery
- `arkis-map.html` — location map embedded in an iframe

## Deploy on GitHub Pages
1. Push the contents of this folder to the repo root (or to `/docs`).
2. Settings → Pages → Source: *Deploy from a branch* → branch `main`, folder `/ (root)` (or `/docs`).
3. Live at `https://<user>.github.io/<repo>/`.

## Local preview
Open `index.html` directly, or serve the folder:
```
python3 -m http.server 8000
```

Notes: filenames contain spaces and parentheses — keep them as-is, the HTML references them exactly. Google Fonts (Cormorant Garamond, Jost) load from the network.
