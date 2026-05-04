# Hand Tracking Games

Browser-based hand-tracking mini-games built with MediaPipe Hands, vanilla JavaScript, and HTML5 canvas.

[![License](https://img.shields.io/github/license/ali-ezz/hand-tracking-games)](LICENSE) [![Top language](https://img.shields.io/github/languages/top/ali-ezz/hand-tracking-games)](https://github.com/ali-ezz/hand-tracking-games) [![Issues](https://img.shields.io/github/issues/ali-ezz/hand-tracking-games)](https://github.com/ali-ezz/hand-tracking-games/issues)

## Overview

This project delivers browser games controlled by hand movement using the webcam and MediaPipe Hands. It is designed for local demo use, rapid customization, and browser-based interaction without a build step.

## Quick start

1. Clone the repository:
   ```bash
   git clone https://github.com/ali-ezz/hand-tracking-games.git
   cd hand-tracking-games
   ```
2. Start a local server from the project root:
   ```bash
   python3 -m http.server 8000
   ```
3. Open the browser at:
   ```text
   http://localhost:8000
   ```
4. Allow camera access, enter a player name, choose a game, and play.

## Features

- Hand-tracking input powered by MediaPipe Hands via CDN
- Multiple mini-games: fruit slicing, maze navigation, air painting, runner control, and shape tracing
- Persistent local leaderboard per game using `localStorage`
- Responsive canvas rendering with device pixel ratio scaling
- Minimal dependency footprint for easy local hosting and customization

## Usage examples

- Play the Ninja Fruit game by moving your index finger to slice fruits and avoid bombs.
- Use the Maze mode to guide the player through a small maze with your fingertip.
- Create drawings in Paint Air with real-time hand motion and color controls.
- Control vertical movement in Runner mode using hand position.
- Trace shapes and fill coverage to score in Shape Trace.

## Project layout

- `index.html` — entry page, UI, menus, and leaderboard modal
- `js/game.js` — core engine, MediaPipe integration, game modes, scoring, and localStorage
- `js/ui.js` — UI behavior and menu interactions
- `js/net.js` — network/leaderboard helpers (if used)
- `assets/` — optional audio, sprites, and game assets
- `server/` — backend metadata or leaderboard storage utilities
- `LICENSE` — repository license
- `CONTRIBUTING.md` — contribution guidelines
- `CODE_OF_CONDUCT.md` — community standards
- `SECURITY.md` — vulnerability reporting guidance
- `.github/ISSUE_TEMPLATE/` — issue intake templates
- `.github/PULL_REQUEST_TEMPLATE.md` — PR guidance
- `CODEOWNERS` — maintainers and review owners

## Development

If you want to customize or add a new game mode, start by modifying `js/game.js` and adding new mode logic around the existing hand-tracking result handlers.

## Contribution

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening issues or pull requests.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
