# 🏢 Rent Manager

A cozy, single-file browser landlord sim — inspired by the *Rent Please! Landlord Sim* genre. Furnish units, house tenants, collect rent, fulfil requests, and grow your building floor by floor.

> An original game inspired by the landlord-sim genre. All code and emoji/CSS art are original — it is not affiliated with or a copy of any specific commercial game.

### 🔗 Live site: https://harirmdhn.github.io/quest-log/

## 🎮 How to play

1. **Click an empty unit** (🚪) to **furnish** it — a tenant moves in. 🎉
2. Tenants pay rent over time — a **🪙 bubble** appears on the unit. **Tap it to collect**, or hit **💰 Collect All Rent**.
3. **Upgrade units** through furniture tiers (Basic → Deluxe) for more rent and **style points ✨**.
4. **Fulfil tenant requests 📋** for bonus coins and style.
5. **🏗️ Add floors** to unlock more units and build your rental empire.

Rent keeps accruing based on real time, even while you're away (capped so it doesn't overflow).

## ✨ Features

- **🛋️ Decorating with style points** — 5 furniture tiers, each adding style and rent.
- **📋 Tenant requests / quests** — tenants ask for upgrades, gifts, more building style, or timely rent collection; fulfil them for rewards.
- **🏢 Multiple floors** — expand upward; each new floor adds 3 units (price scales).
- **💰 Collect All Rent button** — sweep up every unit's rent in one tap.
- **⭐ Leveling + 📅 day counter**, and a running **style score**.
- **🌙 / ☀️ Dark/light theme toggle** — remembered between visits.
- **💾 Auto-save** — your whole building persists in `localStorage`.

## 🚀 Running it

No build step. It's one HTML file:

```
open index.html
```

Or just visit the live site above.

## 🛠️ Tech

Plain HTML, CSS, and vanilla JavaScript. Rent accrues from real timestamps so it continues between sessions. No frameworks, no npm.
