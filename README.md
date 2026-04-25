# ♞ Universal Reversi

A single-file HTML + JavaScript implementation of [Reversi](https://en.wikipedia.org/wiki/Reversi) with a toroidal (infinite) playing field.

## Features

- **Adjustable board size** — 4×4 up to 16×16 (even sizes)
- **Wrap Horizontal / Wrap Vertical** — connect opposite edges independently; with both enabled the board becomes a seamless toroidal surface where no cell is special
- **vs AI** — greedy opponent that maximises immediate flips
- **Animations** — piece pop-in and flip effects

## How to play

Open `index.html` in any modern browser — no server or dependencies required.

## Rules

Standard Reversi rules apply: place a piece to flank one or more opponent pieces in any of the 8 directions; flanked pieces flip to your colour. The player with the most pieces when neither side can move wins.

With wrapping enabled, flanking lines can cross board edges, opening up strategies impossible on a bounded board.

## Original game

[Reversi on Wikipedia](https://en.wikipedia.org/wiki/Reversi)
