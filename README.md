# Polymarket Edge Stable

A simpler GitHub Pages package designed to be easier to run on iPhone Safari.

## Files
- `index.html`
- `manifest.json`
- `icon-192.png`
- `icon-512.png`
- `.nojekyll`

## Deploy on GitHub Pages
1. Create a public GitHub repo.
2. Upload all files in this folder to the repo root.
3. In GitHub go to **Settings > Pages**.
4. Set **Deploy from a branch**.
5. Choose **main** and **/(root)**.
6. Save.
7. Open the Pages URL in Safari.
8. Use **Share > Add to Home Screen**.

## Notes
- This stable package intentionally does **not** use a service worker.
- That makes it less app-like offline, but much easier to update and debug.
- Manual fair-odds overrides save in browser local storage.
