# Memory Card Game

A simple and fun Memory / Concentration card game built with HTML, CSS, and JavaScript.

![Game Screenshot](./Screenshot%202024-07-14%20000215.png)

Overview

This is a lightweight implementation of the classic memory card matching game. Flip two cards at a time and try to find all matching pairs. The cards are shuffled each time you start or finish the game.

Features

- Responsive layout (desktop and smaller screens)
- Smooth flip and shake animations
- Automatic shuffling and restart when all pairs are matched
- Minimal, dependency-free code (vanilla JavaScript)

How to play

1. Open index.html in a web browser (double-click the file or serve the folder with a static server).
2. Click a card to flip it and reveal the image on the back.
3. Flip a second card to try to match the two images.
4. If the two cards match they stay flipped; otherwise they flip back.
5. When all pairs are matched the board reshuffles and you can play again.

Run locally

Option 1 — Open directly
- Double-click `index.html` in the repository root to open it in your default browser.

Option 2 — Serve with a simple local server (recommended for consistent behavior)
- Using Python 3:

  ```bash
  python -m http.server 8000
  ```

  Then open http://localhost:8000 in your browser.

Project structure

- index.html — Main HTML layout for the game
- style.css — Styles and animations
- script.js — Game logic (shuffling, matching, click handling)
- images/ — Card images and icon assets
- Screenshot 2024-07-14 000215.png — Example screenshot used above

Credits

This project contains code inspired by a CodingNepal tutorial (see comment in `index.html`). Thank you to the original author for the tutorial and assets used for learning.

License

This repository does not include a license file. If you want to reuse or redistribute the code, consider adding a LICENSE file (for example, MIT) or ask the repository owner for permission.
