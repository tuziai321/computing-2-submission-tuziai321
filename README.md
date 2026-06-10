# Realmline

**CID:** 02601389

Realmline is a two-player, turn-based territory board game. Players place their remaining pieces, move one piece up to two orthogonal squares, then build a permanent wall beside the piece they moved. Walls divide the board into territories, and a territory scores only when it contains pieces from one player.

## Project Structure

- `web-app/Module.js` defines the game module API and implementation. Its exported functions are documented with JSDoc and operate on game state objects.
- `web-app/tests/wall-go.test.js` contains the unit tests for the game module.
- `web-app/index.html` provides the web page structure.
- `web-app/default.css` provides the styling.
- `web-app/main.js` connects the browser interface to the game module.
- `docs/` contains the generated JSDoc documentation.



Open `web-app/index.html` in a browser to play the game.
