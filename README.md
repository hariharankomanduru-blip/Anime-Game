# ⚔️ KUNAI LEGACY --- WILL OF FIRE

::: {align="center"}
# 🥷 KUNAI LEGACY

### *WILL OF FIRE --- 3D*

**A fast-paced browser-based 3D kunai combat experience built with
Three.js.**

[![HTML5](https://img.shields.io/badge/HTML5-Game-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub](https://img.shields.io/badge/GitHub-Ready-181717?style=for-the-badge&logo=github)](https://github.com/)

`<br>`{=html}

> **"A blade alone means nothing. It is the will behind it that protects
> people."**

`<br>`{=html}

### 🎮 Throw. Dodge. Survive. Master the Kunai.
:::

------------------------------------------------------------------------

## ✨ About The Game

**Kunai Legacy** is a lightweight 3D browser game where the player
enters an arena, faces incoming enemies, throws kunai, builds power
through kills, and unleashes a devastating special attack.

The game opens with a cinematic-style introduction and dialogue sequence
before dropping the player directly into combat.

It is designed as a single-file web experience, making it extremely easy
to run, modify, and publish.

------------------------------------------------------------------------

## 🎬 Experience Flow

``` text
          ┌───────────────────┐
          │   🔥 INTRO SCREEN │
          │   KUNAI LEGACY    │
          └─────────┬─────────┘
                    │
                    ▼
          ┌───────────────────┐
          │ 🎞️ STORY CUTSCENE │
          │  Minato → Naruto  │
          └─────────┬─────────┘
                    │
                    ▼
          ┌───────────────────┐
          │ ⚔️ 3D ARENA       │
          │ Fight + Move      │
          └─────────┬─────────┘
                    │
              15 KILLS
                    │
                    ▼
          ┌───────────────────┐
          │ 🏆 VICTORY        │
          │ WILL OF FIRE      │
          └───────────────────┘
```

------------------------------------------------------------------------

# 🌟 Features

## 🎞️ Cinematic Introduction

The game starts with a dramatic intro screen featuring:

-   🔥 **KUNAI LEGACY** title treatment
-   Japanese-inspired typography
-   Animated/fading screen transitions
-   Story dialogue
-   Minato and Naruto-inspired silhouettes
-   A passing kunai animation
-   Skip button for players who want to enter combat immediately

The interface uses **Bebas Neue** and **Noto Sans JP** for its visual
identity.

------------------------------------------------------------------------

## ⚔️ Kunai Combat

The **kunai is the primary weapon**.

### Throwing

Press:

``` text
SPACE
```

or use the on-screen:

``` text
THROW
```

button.

Each thrown kunai travels through the arena and can eliminate an enemy
on impact.

------------------------------------------------------------------------

## 💥 Special Power

Every enemy defeated increases the player's power meter.

``` text
Enemy defeated
      ↓
+18 Power
      ↓
Power reaches 100%
      ↓
SPECIAL READY
      ↓
Q / SPECIAL
      ↓
Area attack
```

The special attack affects enemies within an **11-unit radius** around
the player.

------------------------------------------------------------------------

## 🔥 Combo System

Rapid eliminations create combo announcements:

``` text
2 KILLS → DOUBLE KILL!
3 KILLS → TRIPLE KILL!
4 KILLS → MEGA KILL!
5 KILLS → ULTRA KILL!
6+     → RAMPAGE!!
```

Combo text uses a punchy scale-and-fade animation to make successful
attacks feel more impactful.

------------------------------------------------------------------------

# 🌦️ Dynamic Weather

Choose the battlefield atmosphere during gameplay.

  Weather        Effect
  -------------- -----------------------------------------------------
  ☀️ **Sunny**   Bright blue environment and stronger sunlight
  🌧️ **Rain**    Darker atmosphere with falling rain
  ⛈️ **Storm**   Heavy rain, darker environment and random lightning

### Storm Mode

Storm weather introduces:

-   🌧️ Fast rain particles
-   ⚡ Random lightning flashes
-   🌑 Darker atmosphere
-   🔥 Red/orange lighting

Switch weather directly from the game HUD.

------------------------------------------------------------------------

# 🎮 Controls

  Action           Keyboard   On-Screen
  ---------------- ---------- -----------
  Move Forward     `W`        ---
  Move Backward    `S`        ---
  Move Left        `A`        ---
  Move Right       `D`        ---
  Throw Kunai      `SPACE`    `THROW`
  Special Attack   `Q`        `SPECIAL`

### Objective

> **Defeat 15 enemies before your health reaches zero.**

------------------------------------------------------------------------

# ❤️ HUD

During combat, the HUD displays:

``` text
┌──────────────────────────────────────────────┐
│ HEALTH ████████████████     KILLS 7 / 15    │
│                                              │
│ POWER  ████████████                         │
└──────────────────────────────────────────────┘
```

### Health

Enemies damage the player when they get close.

### Kills

Track your progress toward the required **15 eliminations**.

### Power

Build power by defeating enemies. At **100%**, the special attack
becomes available.

------------------------------------------------------------------------

# 🥷 Enemy System

Enemies continuously chase the player inside the arena.

Their behavior includes:

-   👣 Movement toward the player
-   🎯 Directional facing
-   🦵 Walking animation
-   ❤️ Contact damage
-   ♻️ Respawning after elimination

Defeating an enemy immediately contributes to the kill counter and power
meter.

------------------------------------------------------------------------

# 🧊 3D Technology

The game is powered by **Three.js** and uses:

-   WebGL rendering
-   Perspective camera
-   Dynamic lighting
-   Shadows
-   Fog
-   3D meshes
-   Particle effects
-   Animated characters
-   Procedural arena elements
-   Real-time game loop

The project currently uses:

``` html
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
```

------------------------------------------------------------------------

# 🎨 Visual Design

The interface combines:

-   🔥 Orange/gold accent colors
-   🌌 Dark cinematic backgrounds
-   ⚡ Glow effects
-   🥷 Ninja-inspired silhouettes
-   🎞️ Screen fade transitions
-   💫 Special-attack flashes
-   💥 Animated combo typography
-   🌧️ Weather particles

The UI is intentionally designed to feel more like an
**arcade/anime-inspired combat interface** than a traditional webpage.

------------------------------------------------------------------------

# 📁 Project Structure

The current project is intentionally simple:

``` text
kunai-legacy/
│
├── kunai-3d.html
└── README.md
```

Everything required for the current game experience is contained inside:

``` text
kunai-3d.html
```

This includes:

-   HTML interface
-   CSS styling
-   JavaScript game logic
-   Three.js scene
-   Player
-   Enemies
-   Kunai system
-   Weather system
-   Combat
-   HUD
-   Cutscene
-   Victory/defeat screens

------------------------------------------------------------------------

# 🚀 Run Locally

## 1. Clone the repository

``` bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

## 2. Enter the project

``` bash
cd YOUR_REPOSITORY
```

## 3. Launch the game

Open:

``` text
kunai-3d.html
```

in a modern browser.

### Recommended browsers

-   Google Chrome
-   Microsoft Edge
-   Firefox

------------------------------------------------------------------------

# 🌐 No Build System Required

One of the project's advantages is its simplicity.

There is currently no:

``` text
npm install
npm run build
webpack
vite
```

required for the basic game.

It's a straightforward:

``` text
HTML
  +
CSS
  +
JavaScript
  +
Three.js
```

experience.

------------------------------------------------------------------------

# 📈 Game Loop

The core gameplay follows this cycle:

``` text
        ┌──────────────┐
        │  ENTER ARENA │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │ FIND ENEMIES │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │ THROW KUNAI  │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │ DEFEAT THEM  │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │ BUILD POWER  │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │ SPECIAL MOVE │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │   15 KILLS   │
        └──────┬───────┘
               ▼
        ┌──────────────┐
        │   VICTORY    │
        └──────────────┘
```

------------------------------------------------------------------------

# 🛠️ Customization

Because the project is contained in one HTML file, it is easy to
experiment with the game.

You can customize:

### 🎨 Colors

The main UI palette is controlled by CSS variables:

``` css
:root{
  --accent:#ff6a1a;
  --accent2:#ffcf5c;
  --blue:#38c8ff;
}
```

### 🎯 Victory Requirement

The current target is:

``` javascript
kills >= 15
```

### ⚡ Power Gain

Each enemy currently provides:

``` javascript
power + 18
```

### 🏃 Player Speed

The current movement speed is:

``` javascript
SPEED = 6.2
```

### 🌧️ Rain

The rain particle system currently uses:

``` javascript
RAIN_COUNT = 700
```

------------------------------------------------------------------------

# 🔮 Future Ideas

The project can be expanded into a much larger ninja combat game.

Possible additions:

-   🌀 Multiple special abilities
-   🗡️ Different kunai types
-   👹 Multiple enemy classes
-   👑 Boss battles
-   ❤️ Enemy health bars
-   💨 Dash ability
-   🧱 Destructible environments
-   🌲 More detailed environments
-   🎵 Background music
-   🔊 Combat sound effects
-   💥 Hit particles
-   🔥 Fire-style abilities
-   ⚡ Lightning kunai
-   ❄️ Ice attacks
-   🏆 High-score system
-   💾 Save system
-   📱 Better mobile controls
-   🎮 Gamepad support
-   🗺️ Multiple arenas
-   🎬 Expanded story cutscenes

------------------------------------------------------------------------

# 👨‍💻 Creators

::: {align="center"}
### 🔥 Created by

**D.SUPREETH**\
**K.HARIHARAN**

------------------------------------------------------------------------

### 🥷 KUNAI LEGACY

*WILL OF FIRE --- 3D*

**Throw with precision.\
Fight with purpose.\
Carry the legacy.**
:::

------------------------------------------------------------------------

# 📜 Credits

### Three.js

The 3D rendering engine is provided by **Three.js**.

### Fonts

The interface uses:

-   **Bebas Neue**
-   **Noto Sans JP**

Fonts are loaded through Google Fonts.

### CDN

Three.js is loaded through cdnjs.

------------------------------------------------------------------------

# ⚠️ Notes

This is a browser-based experimental 3D game project.

The current version focuses on gameplay experimentation, visual effects,
animation, weather, and a lightweight single-file architecture.

The game is not intended to reproduce official assets from any existing
franchise; its characters and presentation are implemented using simple
procedural geometry and original interface code.

------------------------------------------------------------------------

::: {align="center"}
## ⚔️ READY?

# `PRESS SPACE`

### AND LET THE KUNAI FLY.

🔥 **WILL OF FIRE** 🔥
:::
