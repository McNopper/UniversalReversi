# ♞ Universal Reversi

A single-file HTML + JavaScript implementation of [Reversi](https://en.wikipedia.org/wiki/Reversi) with a toroidal (infinite) playing field.

## Features

- **Configurable board size** — 4×4 up to 16×16 (even sizes, default 8×8)
- **Toroidal board** — opposite edges connect seamlessly; no cell is an edge, no cell is special
- **vs AI** — greedy opponent that maximises immediate flips
- **Pan the view** — use ↑↓←→ or the on-screen d-pad to scroll around the infinite board
- **Animations** — piece pop-in and flip effects

## How to play

Open `index.html` in any modern browser — no server or dependencies required.

## Rules

Standard Reversi rules apply: place a piece to flank one or more opponent pieces in any of the 8 directions; flanked pieces flip to your colour. The player with the most pieces when neither side can move wins.

Because the board is toroidal, flanking lines can cross any edge and wrap around, opening up strategies impossible on a bounded board.

## Credits

- **Original Reversi** — invented by [Lewis Waterman and John W. Mollett](https://en.wikipedia.org/wiki/Reversi) (1883)
- **Toroidal variant & concept** — Norbert Nopper 💡
- **Implementation** — GitHub Copilot (AI) 🤖
