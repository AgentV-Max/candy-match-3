# Candy Match 3

A complete, playable match-3 puzzle game (Candy Crush style), built as a single self-contained `index.html` file with vanilla HTML, CSS, and JavaScript — no build step, no dependencies.

## Play

Open `index.html` directly in any modern browser, or serve the repo with any static file host (e.g. GitHub Pages).

## Features

- 8x8 grid with 5 distinct candy types
- Swap adjacent candies by click-then-click or click-and-drag (mouse and touch)
- Only swaps that create a match of 3+ are allowed; invalid swaps revert
- Matches clear, candies fall to fill gaps, and new candies drop in from the top
- Cascading matches are detected and resolved automatically, with a combo score multiplier
- Live score counter and a move counter (starts at 30, counts down)
- Reset button to start a new game
- Automatic reshuffle if no legal moves remain
- Smooth CSS transitions for swaps/falls and a pop animation when candies clear

## Tech

Everything lives in `index.html` — HTML structure, CSS styling/animations, and the game logic in vanilla JS, wrapped in an IIFE with no external libraries.
