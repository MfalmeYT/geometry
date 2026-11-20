# Game Hub

Static game portal. No build step, no external requests.

## Add a game
1. Put the game in `games/<name>/` (it needs an `index.html`).
2. Add an entry to `games.json`:
   `{ "id": "name", "title": "Name", "category": "Arcade", "path": "games/name/index.html", "thumb": "" }`
   `thumb` is optional (e.g. `games/name/thumb.png`); a colored tile is generated otherwise.
Only add games you have the rights to host (your own, open-source, or licensed).

## Deploy
Push to a GitHub repo, then Settings > Pages > deploy from branch `main` / root.
Note: Pages sites are public.

## Controls
- Emergency key (default Ctrl+Y, rebind in settings): closes the game and goes to launchpad.classlink.com
- `/` focuses search, `Esc` closes a game.
