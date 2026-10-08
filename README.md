# Paper Throw

Paper Throw is a browser-based office-themed arcade game where you toss sheets of paper into a bin, hit targets, build streaks, and clear three progressively tougher levels.

Built as a single-file HTML game for quick play in the browser, it is designed for desktop and touch devices and includes a polished UI, sound effects, score tracking, and responsive gameplay.

## Features

- Three difficulty levels with increasing speed and challenge
- Score system with streak bonuses and level progression
- Sound effects and muted toggle control
- Mouse and touch support
- Responsive layout for desktop and mobile screens
- Simple local best-score tracking in browser storage
- No build setup required

## How to Play

1. Open `Paper Throw.html` in a browser.
2. Click or tap the paper pile to begin charging your throw.
3. Drag your cursor or finger to aim.
4. Release when the power indicator is aligned with the target band.
5. Land paper in the bin to score points and complete each level.
6. Reach the required number of successful throws before running out of sheets.

## Controls

- Mouse: click and hold the paper pile, drag, then release
- Touch: tap and hold the paper pile, drag, then release
- Keyboard: Escape closes the help overlay

## Project Structure

- `Paper Throw.html` — the complete game with embedded HTML, CSS, and JavaScript
- `_redirects` — Netlify routing that serves the game at the site homepage
- `README.md` — project documentation

## Run Locally

Because this project is a single static HTML file, you can run it in any modern browser:

Option 1:
- Open `Paper Throw.html` directly in your browser.

Option 2:
- Serve the folder with a local web server, for example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/Paper%20Throw.html
```

## Notes

- On Netlify, the site homepage serves `Paper Throw.html` through a rewrite, so visitors can play directly at `/` without a build step.
- The game stores the best score in browser `localStorage`.
- Sound is enabled by default and can be toggled from the top-right button.
- The project is intentionally lightweight and does not depend on any external libraries or frameworks.

## License

This project is provided as-is for personal and educational use.

## Author

Rishh2005
