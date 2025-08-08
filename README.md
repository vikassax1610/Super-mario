# 🎮 Super Mario Bros Clone

A fan-made **Super Mario Bros** game built using **[Cocos Creator](https://www.cocos.com/en/creator)** and **TypeScript**.  
This project recreates the nostalgic platforming experience of Mario, including running, jumping, collecting coins, defeating enemies, and level completion — all within the Cocos 2D framework.

> ⚠️ This project is for **educational purposes only** and is not affiliated with or endorsed by Nintendo.

---

## 🎥 Gameplay Preview

![Mario Gameplay](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExZnVzOWV0NGVkbW10dnhubTZxZnQ1bjM4aDd2NDRvdGRzZ2g0Z3BrayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l1IY5CmYbirEsXWPm/giphy.gif)

---

## ✨ Features

- 🎯 **Classic Mario Mechanics** — Running, jumping, enemy stomping, mystery boxes, coins, and flagpole ending.
- 🧩 **Prefabs for Reusability** — Players, enemies, obstacles, and collectibles are created as reusable prefabs.
- 🌍 **Tilemap-based Levels** — Designed in Cocos Creator for smooth collisions and map design.
- 🎨 **Pixel Art Sprites** — Retro-inspired graphics faithful to the original.
- 🎵 **Background Music & SFX** — For a nostalgic feel.
- 🛠 **TypeScript with Cocos Creator** — Strong typing, clean architecture, and easy debugging.

---

## 🛠 Tech Stack

- **Cocos Creator** (v3.x+)
- **TypeScript**
- **Cocos Physics 2D** (Box2D for collisions)
- Sprite Animations & Prefabs
- Audio Components for music and SFX

---

## 📂 Project Structure

├── assets/
│ ├── scripts/
│ │ ├── PlayerController.ts
│ │ ├── Enemy.ts
│ │ ├── MysteryBox.ts
│ │ ├── Coin.ts
│ │ ├── GameManager.ts
│ │ └── ...
│ ├── textures/ # Sprites & tilesets
│ ├── audio/ # Background music & sound effects
│ └── tilemaps/ # Level maps
├── scenes/
│ ├── Level1.scene
│ └── MainMenu.scene
├── README.md
└── package.json


---

## 🚀 Getting Started

### 1️⃣ Prerequisites
Make sure you have:
- [Cocos Creator v3.x+](https://www.cocos.com/en/creator) installed
- Node.js (for TypeScript compilation, optional)
- Basic knowledge of Cocos Creator’s Editor

---

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/vikassa816/super-mario
cd super-mario
