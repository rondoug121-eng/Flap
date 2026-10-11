FLAPPY RETRO HUD UPDATE

Files in this package:
- game.js: lowers the score HUD and pause button, gives them a more polished translucent treatment, and updates the pause-button tap zone to match the new position.
- index.html: adds a version query to game.js and bumps the service worker registration version so phones refresh the updated script.
- sw.js: bumps the offline cache version to v4.

To publish on GitHub from an iPhone:
1. Open https://github.com/yw6bdt7v7t-arch/flappy-retro
2. Open each file (game.js, index.html, sw.js) and choose Edit (pencil menu).
3. Replace the file contents with the matching file from this package, then commit the changes.
4. Reload the game. If an installed home-screen copy still shows the old version, close it fully and reopen it, or open the website in Safari once to refresh the cache.

The game.js was checked for JavaScript syntax. The original bird physics, pipe spacing, scoring progression, visuals, and gameplay rules were kept intact; only the HUD placement/styling and pause hit zone were changed.
