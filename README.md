# ChessForge 2000 — iPhone PWA v0.2

## What works
- Responsive chessboard with legal moves (castling, en passant, check detection and promotion-to-queen in free board)
- Four starter exercises (some are introductory and deliberately simple)
- Hints, undo, restart, next exercise
- Local statistics and JSON backup
- Service-worker offline caching after first successful HTTPS load
- Add to Home Screen in Safari after HTTPS deployment

## Not yet included
- Stockfish evaluation, Chess.com API/PGN import, full adaptive training, sync across devices
- Draw claims, repetition, move clocks, promotion piece chooser, multiplayer
- Puzzle set is an initial demonstration, not a validated high-quality training corpus

## Host for free
Upload the contents of this folder (not the ZIP itself) to a static HTTPS host such as GitHub Pages, Cloudflare Pages or Netlify. Open the HTTPS link in iPhone Safari; Share → Add to Home Screen. Once the service worker has cached the files, core functionality works offline. Hosting and a publicly accessible URL are not created automatically.

## Local development
`python3 -m http.server 8000` then open http://localhost:8000 in a desktop browser. Service workers generally require HTTPS or localhost.

## Data privacy
Training counters are kept in browser localStorage. Export JSON backups before clearing browser data. No user account, analytics, or remote data collection.
