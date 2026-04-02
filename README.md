# Web Pong

A single-player browser Pong game — you vs a computer AI. First to 21 wins.

## How to Play

Open `index.html` in any modern browser. No build step, no dependencies.

- **Move paddle**: Arrow Up / Arrow Down
- **Goal**: Get the ball past the CPU's paddle
- **Win condition**: First to 21 points

## Features

- HTML5 Canvas rendering
- 8-bit sound effects via Web Audio API (paddle hit, wall bounce, scoring)
- Scaling AI difficulty based on your score:
  - **0–6 pts**: Easy
  - **7–13 pts**: Medium
  - **14–20 pts**: Hard
- Start screen, live scoreboard, and win/lose screen
