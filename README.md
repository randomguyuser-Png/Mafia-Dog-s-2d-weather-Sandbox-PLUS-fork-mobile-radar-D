# Mafia-Dog-s-2d-weather-Sandbox-PLUS-fork-mobile-radar-
hi guys!my first fork:D

#About it
have mobile radars like
TTUKa
DOW 3,6,8
RAXPOL
Have vehicle
Chevrolet Cobalt(in future i will add more)

new Brush-
Vortex Brush - make Vortices that can pull water vapor/cloud and take down radars for some seconds
Tornado Vortex - Make Funnels that can lift over cars WARNING this brush have one of the most dangerous bugs ever of this project,it's called wall killer of simulations,when you are tryng to generate a tornado
a cloud starts to expand itself to it's limits until get on the map's limit and crash you simulation!
Supercell Maker
Make supercells in seconds
#Credits
Boruq on discord(he made 2d Weather Sandbox Plus!)







How to run it locally and modify code
Quick start (game + multiplayer)
npm install
npm start
Open http://localhost:8080 in your browser. Multiplayer works automatically — no separate relay terminal.

VS Code + Live Server (single-player only)
Install VS code: https://code.visualstudio.com/
Install VS Code extensions:
Live Server (required)
GLSL lint (recommended)
Clang-Format, requires installing CLANG/LLVM: https://github.com/llvm/llvm-project/releases/tag/llvmorg-16.0.0 (recommended)
Clone project using GIT, or just download ZIP
Open project folder in VS Code
Open index.html
Start live server (Go Live), automatically opens page in browser
Note: Live Server does not include multiplayer. Use Open in browser in the menu (points at GitHub Pages) or run npm start for local multiplayer.

Deploy online (GitHub Pages — recommended)
The game is hosted on GitHub Pages so it stays free and does not depend on Render monthly quotas.

Push to GitHub (main branch).
In the repo go to Settings → Pages → Source: GitHub Actions (the included .github/workflows/deploy-pages.yml deploys automatically on push to main).
When the workflow finishes, open https://weatherin2d.github.io/2D-Weather-Sandbox-Extra/
In repo Settings → General → Website, set the URL to the same GitHub Pages link.
network/config.js and package.json homepage already point at this URL for local copies and the “Open in browser” button.

Optional: Render (multiplayer relay)
If you still want a Node server with WebSocket relay (e.g. when Render quota is available), use render.yaml on Render.com. Free tier sleeps after inactivity; first connection may take ~30 seconds.

Local multiplayer (WIP)
Who	What to do
Host	npm install then npm start → open http://localhost:8080 → Host Game (optional room password)
Friends (same network)	Open the host's http://<host-ip>:8080 → Join Game with room code (and password if set)
Room codes are 8 characters. The relay limits payload size and rate-limits connections. Multiplayer is experimental — expect lag, desync, or broken sessions.

Sounding imports use a CORS proxy; only meteociel.fr hosts are allowed client-side. Override the proxy base with window.__WEATHER_CORS_PROXY if you host your own Worker (restrict it to those hosts).
