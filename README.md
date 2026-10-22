# Obbylox 🏃‍♂️ (3D Obby)

A 3D browser obby game with an Arabic interface: a lobby, a name and colour screen, a portal into the course, and 5 stages with checkpoints. One file: `index.html` (uses Three.js from a CDN, so it needs internet).

## Play locally
Open `index.html` in your browser.

## Controls
- Move: `W A S D` or arrow keys
- Jump: `Space` (hold for a higher jump)
- Camera: drag with the mouse, scroll to zoom
- Mobile: on-screen joystick and jump button

## How to play
1. Enter your name and pick a colour, then press "ادخل اللعبة".
2. Walk into the glowing portal in the lobby to start the obby.
3. Reach each green checkpoint, avoid the red bricks and don't fall.
4. Reach the golden platform at the end to win.

## Put it on GitHub + play online (GitHub Pages)
1. Create a new repository on github.com
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` / `(root)`, and Save
4. Your game will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Customize
Edit the `buildObby()` function in `index.html`. Platforms are made with `addBox(x, y, z, w, h, d, color, options)`. Use `{ move: {...} }` for moving platforms and `{ kill: true }` for red hazard bricks.

## Credits
Made by **Abdulrhman Alsnaidi** (abdulrhman)
