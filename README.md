# Tic-Tac-Toe Game

A simple, responsive Tic-Tac-Toe web game built with HTML, CSS, and JavaScript.

## Demo

Open `index.html` in a browser to play the game locally.

## Table of Contents

* [About](#about)
* [Features](#features)
* [How to Play](#how-to-play)
* [Files](#files)
* [Installation & Usage](#installation--usage)

## About

This project implements the classic Tic-Tac-Toe (Noughts and Crosses) game using plain HTML, CSS, and JavaScript. The UI is lightweight and easy to extend, making it a good starter project for learning DOM manipulation and game logic.

## Features

* 3×3 game grid
* Two-player gameplay (X vs O)
* Win/tie detection
* Reset and New Game functionality
* Responsive layout and basic accessibility
* Sections for rules, game overview, contact, and more in the UI

## How to Play

1. Players take turns clicking an empty square to place their mark (X or O).
2. The first player to place three of their marks in a horizontal, vertical, or diagonal row wins.
3. If all 9 squares are filled without a winner, the game ends in a tie.

## Files

```
/ (project root)
├─ index.html        # Main HTML file (your provided markup)
├─ style.css         # Styles for layout and responsive behavior
├─ script.js         # Game logic: click handlers, win detection, reset
├─ README.md         # This file
```

## Installation & Usage

1. Clone or download the repository:

  git clone https://github.com/bhupendrar1

2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).

No build step or server is required. If you prefer, you can serve the folder with a simple static server (for example `npx http-server` or VS Code Live Server).

## Suggested `script.js` behavior (quick reference)

* Attach click listeners to each `.box` element.
* Track the current player (`'X'` or `'O'`).
* On click: place mark, check for win/tie, toggle player.
* Show a message overlay when game ends and provide `New Game` and `Reset Game` actions.

## Customization

* Change the look in `style.css` — colors, spacing, fonts.
* Add single-player vs. CPU mode with a simple minimax AI or heuristic.
* Add scorekeeping between rounds.
* Add animations for mark placement and win highlight.



