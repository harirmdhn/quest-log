# 🌱 Pocket Farm

A cozy, single-file browser farming game. Plant seeds, wait for them to grow, harvest for coins, and expand your little farm.

### 🔗 Live site: https://harirmdhn.github.io/quest-log/

## 🎮 How to play

1. **Pick a seed** from the row at the top.
2. **Click an empty plot** to plant it (costs coins).
3. **Wait** — crops grow through 🌱 → 🌿 → ripe. A progress bar shows how close they are.
4. **Click a ripe plot** to harvest it for coins and XP (or use **Harvest All**).
5. **Spend coins** on more plots, and **level up** to unlock better crops.

Crops keep growing even while the tab is closed, so you can check back later. 🌾

## ✨ Features

- **🌾 Five crops** — Carrot, Corn, Strawberry, Pumpkin, and Melon — each with its own grow time, cost, and payout.
- **📈 Leveling system** — earn XP to unlock higher-value crops.
- **🧺 Expandable farm** — buy more plots (price scales as you grow).
- **⏳ Offline growth** — crops ripen based on real time, even while away.
- **🪙 Juicy feedback** — coins pop when you harvest, chips bump, crops wiggle when ready.
- **🌙 / ☀️ Dark/light theme toggle** — remembered between visits.
- **💾 Auto-save** — your whole farm persists in `localStorage`.

## 🚀 Running it

No build step. It's one HTML file:

```
open index.html
```

Or just visit the live site above.

## 🛠️ Tech

Plain HTML, CSS, and vanilla JavaScript. Growth is tracked with real timestamps so progress continues between sessions. No frameworks, no npm.
