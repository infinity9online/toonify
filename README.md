# Toonify

Toonify is a fast, browser-based **TOON ⇄ JSON formatter, converter, and inspector**.

- 🔁 Convert TOON → JSON and JSON → TOON
- ⚡ Auto-detect input format (TOON or JSON)
- 🧹 Format TOON via round-trip encode/decode
- 🌳 JSON tree view inspector
- 📋 Copy, ⬇️ download, ⬆️ upload
- 🔗 Shareable links with data & settings
- 🌓 Light / dark theme with persistence
- 🎯 Drag & drop files or text

## Usage

Just open **index.html** in any modern browser (no build step, no backend).

## Deploy

### Vercel

- Create a new Vercel project
- Set the root folder to this repo
- Vercel will pick up `vercel.json` and serve `index.html` for all routes

### Netlify

- Drag & drop this folder into Netlify, or connect the GitHub repo
- Netlify will use `netlify.toml` and publish `index.html` as a static site

## Development

Everything lives in `index.html` (HTML, CSS, JS).
The app uses the official **@toon-format/toon** package via CDN.

