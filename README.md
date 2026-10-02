# 🔴🟡 Connect Four — vs AI

A single-file, zero-dependency Connect Four game you play against a computer opponent in the browser.

### 🔗 Live site: https://harirmdhn.github.io/quest-log/

## ✨ Features

- **🤖 Play vs AI** — the computer uses a minimax algorithm with alpha-beta pruning and a position-scoring heuristic.
- **🎚️ Difficulty levels** — Easy, Medium, Hard, and Brutal (increasing AI search depth).
- **↕️ Choose who goes first** — you or the AI.
- **🎬 Smooth drop animations** and a winning-four highlight pulse.
- **🌙 / ☀️ Dark/light theme toggle** — your choice is remembered between visits.
- **🏆 Score tracking** — Wins / Draws / Losses saved in `localStorage`.

## 🎮 How to play

Click a column (or the ▾ button above it) to drop your red disc. Get four in a row — horizontally, vertically, or diagonally — before the AI does. Red is you, yellow is the AI.

## 🚀 Running it

No build step. It's one HTML file:

```
open index.html
```

Or just visit the live site above.

## 🛠️ Tech

Plain HTML, CSS, and vanilla JavaScript. The AI is a classic minimax search with alpha-beta pruning, center-first move ordering, and a windowed board-evaluation heuristic. No frameworks, no npm.
