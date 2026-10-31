# Jade Rails

A train route-building board game across East Asia, Germany or France, for 1 player against 1–3 bots (Easy, Medium, Hard).

Open `jade-rails.html` in any browser. No install, no server, works offline.

- Draw train cards, claim routes between cities, and connect your destination tickets.
- The game autosaves in your browser; reopen the file to resume.
- Zoom with trackpad scroll or pinch, drag to move the map.

## Play online with friends

One player clicks **Host a room** and shares the 4-letter code (or the link). Friends type their name, enter the code and click **Join**. The host can fill empty seats with bots, up to 4 players.

- The host's browser runs the game: if the host closes the tab, the game ends.
- A friend who drops out can rejoin with the same name and room code.
- Browsers connect directly via [PeerJS](https://peerjs.com); its free public server only introduces them. Online play needs internet; solo play still works offline.
- To share a link, the file must be served from a web address (e.g. GitHub Pages), not opened from disk.

Bot self-check: open the browser console and run `simulate()`.

Map geography (coastlines, borders, rivers, lakes) comes from [Natural Earth](https://www.naturalearthdata.com), public domain. Shaded relief is baked from [AWS Terrain Tiles](https://registry.opendata.aws/terrain-tiles/) elevation data (SRTM, ETOPO1 and others).
