# ChessForge 2000 v0.3 update

Upload the following **five files** into the root of your existing GitHub repository, replacing four existing files and adding `importer.js`:

- `index.html` (replace)
- `app.js` (replace)
- `style.css` (replace)
- `sw.js` (replace)
- `importer.js` (new)

Keep existing `engine.js`, `manifest.webmanifest`, `icon.png`, and `icon-512.png` unchanged. Do not delete your existing repository files.

After committing, allow GitHub Pages to deploy, then refresh the app. On iPhone, you may need to close and reopen the Home Screen app to pick up the updated service worker.

Tap **Sync Chess.com** to attempt downloading the six latest monthly public archives for username `Pandu212`. If blocked by network/CORS or unavailable, use **Import PGN file**. PGN import filters to Rapid games using Event or time control metadata. Imported game metadata is saved locally. This version does not calculate engine accuracy, blunders, or centipawn loss.
