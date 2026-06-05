# 🟦 Tetris — Web Edition

A clean, production-ready Tetris clone built with vanilla HTML5, CSS3, and JavaScript. Zero dependencies. One file. Fully playable in the browser.

![Tetris Screenshot](https://img.shields.io/badge/version-1.0.0-00f5c4?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square) ![Vanilla JS](https://img.shields.io/badge/stack-Vanilla%20JS-f5c400?style=flat-square)

---

## 🎮 Live Demo

Open `index.html` in any modern browser — no server required.

Or deploy to GitHub Pages:

1. Go to your repo → **Settings → Pages**
2. Set source to **main branch / root**
3. Visit `https://<your-username>.github.io/<repo-name>`

---

## ✨ Features

- All 7 standard tetrominoes (I, O, T, S, Z, J, L)
- Ghost piece — shows landing position
- Progressive speed (10 levels)
- Scoring system (single/double/triple/tetris bonuses × level)
- Next-piece preview
- Pause support
- Touch/swipe support for mobile browsers
- Retro cyberpunk aesthetic with no external dependencies (just a Google Font)

---

## 🕹️ Controls

| Key / Gesture | Action |
|---|---|
| `←` / `→` | Move left / right |
| `↑` | Rotate clockwise |
| `↓` | Soft drop |
| `Space` | Hard drop |
| `P` | Pause / resume |
| Tap | Rotate (mobile) |
| Swipe left/right | Move (mobile) |
| Swipe down | Hard drop (mobile) |

---

## 📁 Project Structure

```
tetris/
├── index.html   # Complete game — HTML + CSS + JS in one file
└── README.md
```

---

## 🏆 Scoring

| Lines cleared | Points (× level) |
|---|---|
| 1 (Single) | 100 |
| 2 (Double) | 300 |
| 3 (Triple) | 500 |
| 4 (Tetris!) | 800 |

Level increases every 10 lines cleared, capped at level 10.

---

## 🚀 Running Locally

```bash
git clone https://github.com/<your-username>/tetris.git
cd tetris
open index.html   # macOS
# or: start index.html   # Windows
# or: xdg-open index.html  # Linux
```

No build tools, no `npm install`, no bundler.

---

## 📄 License

MIT © 2025
