# Screw Studio

Chopped & screwed remix studio. Created by Wesscoastt.

Drop a song, it finds the BPM, key, and structure, screws it to the right speed,
and places chops on the beat. Everything is editable after. Runs entirely in the
browser — no server, nothing uploaded anywhere.

## Files
- `index.html` — the whole app
- `sw.js` — service worker (offline support). Bump `CACHE_VERSION` when index.html changes
- `manifest.json`, `icon-180.png`, `icon-512.png` — install-to-home-screen support

## Hosting
Built for Cloudflare Pages: no build step, output directory is the repo root.
