# 🏜️ The Lost Oasis

![The Lost Oasis Banner](screenshots/thumbnail.png)

> A competitive desert adventure built in Roblox Studio — explore sand dunes, find 25 hidden ancient coins, and compete with other players to top the leaderboard!

---

## 🎮 Play the Game

🔗 [Play on Roblox](https://www.roblox.com/games/90625758455741)

---

## 📸 Screenshots

| Gameplay | Oasis |
|----------|-------|
| ![Gameplay 1](screenshots/gameplay1.png) | ![Oasis](screenshots/oasis.png) |

**Mobile:**

<img src="screenshots/mobile.png" width="300"/>

---

## 🗺️ Map Overview

| Isometric View | Top View |
|----------------|----------|
| ![Map Isometric](screenshots/map_iso.png) | ![Map Top](screenshots/map_top.png) |

---

## ✨ Features

- 🌵 **Fully sculpted desert terrain** — procedurally generated sand dunes using Roblox's Terrain Editor
- 💧 **Oasis water pools** — scattered naturally across the desert landscape
- 🏚️ **Desert hut structures** — explorable buildings placed throughout the world
- 🎵 **Ambient desert music** — looping sand storm atmospheric soundtrack
- 📱 **Cross-platform** — fully playable on both PC and mobile devices
- ☀️ **Immersive atmosphere** — dynamic lighting and fog for a realistic desert feel
- 🪙 **25 hidden ancient coins** — scattered across the desert map to find and collect
- 🏆 **Live leaderboard** — compete with other players to see who collects the most coins
- 📊 **Coin counter UI** — tracks your progress on screen at all times

---

## 🛠️ Built With

| Tool | Purpose |
|------|---------|
| **Roblox Studio** | Game development environment |
| **Roblox Terrain Editor** | Desert terrain sculpting and painting |
| **Lua scripting** | Spawn logic and game mechanics |
| **Roblox Toolbox** | Desert hut and cactus assets |

---

## 🧱 Development Highlights

- Used the **Terrain Editor's Sea Level tool** to place oasis water pools naturally within desert depressions
- Solved a **mobile spawning bug** by fine-tuning SpawnLocation Y-position to align with terrain surface
- Implemented a **Lua respawn script** to handle terrain loading differences between PC and mobile
- Added **ambient sandstorm music** via SoundService with looped playback for an immersive desert atmosphere
- Designed custom **game icon and thumbnail** assets at 512×512 and 1024×576 resolutions
- Built a **coin collection system** using Lua touch detection and ServerScript logic
- Created a **real-time leaderboard and HUD** using ScreenGui, LocalScript, and IntValue data binding

---

## 📁 Project Structure

```
The Lost Oasis (Roblox Studio)
├── Workspace
│   ├── Terrain          # Desert biome with sand material
│   ├── Sound            # Looping ambient sandstorm music
│   ├── SpawnLocation    # Player spawn point
│   ├── Cactus (x20)    # Desert cactus models
│   ├── Hut (x2)        # Explorable desert structures
│   ├── Artifact (x25)  # Collectible ancient coins
│   └── Parts            # Water/oasis elements
├── ServerScriptService
│   └── Script           # Spawn, leaderboard, and coin logic
└── StarterGui
    └── ScreenGui        # Coin counter and leaderboard UI
```

---

## 👨‍💻 Developer

**Rayane** — [@rayane_drh1](https://www.roblox.com/users/9321040316/profile)

Junior Computer Science student at Alma College  
Built as part of **CSC-355: Game Engine Fundamentals**

---

## 📄 License

This project was built for educational purposes as part of a university course.  
All Roblox assets used are sourced from the official Roblox Toolbox.
