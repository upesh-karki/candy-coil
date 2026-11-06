# Candy Coil

A lightweight candy-themed worm arena built with plain JavaScript, CSS, and Canvas 2D. Original artwork, no dependencies, and no game server required.

## Play

Open `index.html` in a browser. Move your mouse or drag on a touchscreen to steer. Hold the mouse button, Space, or the on-screen boost button for extra speed. Press Escape to pause.

## Features

- Arena and Two Teams modes with 18 AI opponents
- Six skins, sweets, growth, boosting and collision mechanics
- Five timed power-ups: speed, agility, magnet, double growth and shield
- Leaderboard, minimap, touch controls, sound and quality settings
- Browser-local best score and saved preferences

This is a local bot game, not online multiplayer. It has no account system, purchases, or shared online scores. It is not affiliated with Wormate.io.

## GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, choose **main** and **/(root)**, then Save. No build step is needed.

## Local development

Edit the three source files directly. Optionally preview with:

```sh
python3 -m http.server 8000
```

The optional Google Fonts stylesheet falls back to system fonts when offline.
