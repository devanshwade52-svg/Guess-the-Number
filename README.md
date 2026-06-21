# 🎯 Guess the Number

A fun and colorful number guessing game built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, just open and play!

## 🎮 How to Play

1. The game picks a secret number between **1 and 100**
2. Type your guess and hit **Submit** (or press `Enter`)
3. You'll get a hint — **too high** or **too low**
4. Keep guessing until you find it!

## ✨ Features

- 🌈 **Colorful glassmorphism UI** with a deep purple gradient background
- 📊 **Live range bar** that shrinks as you narrow in on the number
- 📍 **Guess marker** that tracks your last guess on the bar
- 🎨 **Color-coded feedback** — orange for too high, blue for too low, green for correct
- 🕓 **Guess history** with labeled badges (newest on top)
- 🏆 **Best score tracker** across multiple games in the same session
- ✅ **Input validation** with friendly warnings
- ⌨️ **Keyboard support** — just press `Enter` to submit

## 🚀 Getting Started

No installation needed. Just download and open the file:

```bash
git clone https://github.com/your-username/guess-the-number.git
cd guess-the-number
open index.html
```

Or simply double-click `index.html` in your file explorer.

## 🛠️ Built With

- HTML5
- CSS3 (glassmorphism, transitions, gradients)
- Vanilla JavaScript
- [Tabler Icons](https://tabler.io/icons) (via CDN)

## 📁 Project Structure

```
guess-the-number/
└── index.html      # Everything in one file — game logic, styles, and UI
```

## 🧠 Game Logic

The game uses the same core logic as the original Python script — just reimagined for the browser:

```python
import random
choice = random.randint(1, 100)   # →  Math.floor(Math.random() * 100) + 1
```

On top of that, the browser version tracks the valid number range after each guess and narrows the range bar in real time.

## 📸 Preview

> A purple-themed glassmorphism card with a live shrinking range bar, colorful stat cards, and a guess history log.

## 📜 License

MIT — free to use, modify, and share.

---
