# Repository Context

## What this project does
This repository contains a browser-based Memory Game (also called Concentration). It is a single-page web app built with plain HTML, CSS, and JavaScript.

The game lets a player:
- flip cards to reveal symbols
- match pairs to clear the board
- track moves and elapsed time
- rate performance with a star system
- switch between 4x4 and 6x6 layouts
- keep local high scores in browser storage
- use keyboard controls for accessibility

It is designed to run directly in a browser without any external dependencies or build pipeline.

## Project structure
- `memory-game.html` — the full game implementation, styling, and logic in one file
- `README.md` — user-facing overview and quick-start instructions
- `context.md` — this file, summarizing the project purpose and repo context

## How it works
The game creates a shuffled deck of emoji pairs, renders the cards in a grid, and tracks player turns. When two cards match, they remain face-up and are marked as matched. Once all pairs are found, the app records the player's result and displays a win modal and score summary.

## What the repo name means
The project name is `memory-game-GHCP`. The `memory-game` portion is clear and descriptive: it is a memory matching game. The `GHCP` suffix is not defined in the codebase or README, so it appears to be a repository or environment label rather than an acronym with business logic behind it. In practical terms, this repo is simply a small front-end game project named with a label suffix.

## Best way to use it
Open `memory-game.html` in a browser, or serve the folder locally with a simple HTTP server if preferred.

Example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/memory-game.html`.

## Summary
This repo is a lightweight, self-contained memory card game for learning, fun, and browser-based prototyping. It demonstrates front-end interactivity using only core web technologies, without any frameworks or package installation.
