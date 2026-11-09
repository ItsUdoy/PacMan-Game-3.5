# 👾 Pac-Man Classic Arcade Edition (v3.5)

<p align="center">
  <img width="1280" height="640" alt="Pac-Man Classic Arcade Edition Banner" src="https://github.com/user-attachments/assets/77c67a44-78e9-4114-8b4e-3bbf39fdd304" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-orange.svg" alt="Java">
  <img src="https://img.shields.io/badge/GUI-Java%20Swing-blue.svg" alt="Java Swing">
  <img src="https://img.shields.io/badge/Architecture-Single--File-brightgreen.svg" alt="Single File">
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-purple.svg" alt="License">
</p>

An authentic, single-file retro Java Swing arcade game inspired by classic Pac-Man mechanics, enhanced with neon aesthetics, customizable maps, a persistent top-10 leaderboard, dynamic difficulty scaling, and synthesised retro audio.

Developed as an academic team project by **BUP CSE - 4**.

---

## 📑 Table of Contents

- [Screenshots](#-screenshots)
- [Key Features](#-key-features)
- [Controls](#️-controls)
- [Prerequisites & Installation](#️-prerequisites--installation)
- [Maps](#️-maps)
- [Difficulty Levels](#-difficulty-levels)
- [Developers](#-developers)
- [License](#-license)

---

## 📸 Screenshots

| Main Menu | Map Selection |
|:---:|:---:|
| <img width="922" alt="Main Menu" src="https://github.com/user-attachments/assets/4bb776db-1a13-414c-85e2-090b8fe2d308" /> | <img width="920" alt="Map Selection" src="https://github.com/user-attachments/assets/396ec404-1cc0-4275-b625-c88cae2e4050" /> |

| Leaderboard | Developers / About Us |
|:---:|:---:|
| <img width="920" alt="Leaderboard" src="https://github.com/user-attachments/assets/cb1ffd83-8807-4c54-a355-47ef7826c97f" /> | <img width="922" alt="About Us" src="https://github.com/user-attachments/assets/d252d728-6123-4aab-8c05-a75be112f8da" /> |

| How To Play | Exit Confirmation |
|:---:|:---:|
| <img width="922" alt="How To Play" src="https://github.com/user-attachments/assets/820c0cd9-8814-4005-afc4-56e13f88546a" /> | <img width="921" alt="Exit Confirmation" src="https://github.com/user-attachments/assets/ece3dd53-ec54-4035-b915-bb628c6d82fe" /> |

---

## ✨ Key Features

- **🎮 Classic Arcade Gameplay:** Grid-aligned cornering, ghost AI pathfinding, frightened ghost modes, and responsive player movement controls.
- **🗺️ Multiple Selectable Maps:** Three distinct level layouts (see [Maps](#️-maps)).
- **⚡ Dynamic Difficulty:** Play on Easy, Normal, or Hard, affecting ghost baseline speeds and power pellet timers.
- **🏆 Persistent Top 10 Leaderboard:** Uses Java's native `Preferences` API for local score tracking, recording player name, score, map, difficulty, cleared mazes, extra hearts, and completion date.
- **❤️ Extra Life System:** Eating 3 blue ghosts during power food mode grants **+1 Extra Heart** (capped at a maximum of 5 lives).
- **🔊 Synthesised Retro Sound:** Built-in audio generator producing triangle, square, sine, and sawtooth sound effects using the pure `javax.sound.sampled` API (no external MP3/WAV files required).
- **🎨 Pure Retro Aesthetic:** Custom neon glowing borders, retro typography, pixel-art styling, and optional CRT scanline overlay.

---

## 🕹️ Controls

| Key | Action |
|:---|:---|
| **`W` / `↑`** | Move Pac-Man Up |
| **`S` / `↓`** | Move Pac-Man Down |
| **`A` / `←`** | Move Pac-Man Left |
| **`D` / `→`** | Move Pac-Man Right |
| **`P`** | Pause / Resume Game |
| **`Enter` / `Esc`** | Close Modals & Confirm Dialogs |

---

## ⚙️ Prerequisites & Installation

### Requirements

- **Java Development Kit (JDK 11 or higher)**

### How to Run

**1. Clone the repository**

```bash
git clone https://github.com/your-username/pacman-arcade-edition.git
cd pacman-arcade-edition
```

**2. Compile the game**

Replace `PacManGame.java` with your actual Java file name if necessary.

```bash
javac PacManGame.java
```

**3. Run the game**

```bash
java PacManGame
```

---

## 🗺️ Maps

The game features three unique maps, each offering a different maze layout and gameplay experience.

| # | Map | Description |
|:---:|:---|:---|
| 1 | **NEON ARCADE** | Standard arcade grid |
| 2 | **CSE - 4** | Custom department-themed maze |
| 3 | **ZIGZAG HALLS** | High-density corridor layout |

---

## ⚡ Difficulty Levels

Choose from three difficulty levels to customize your arcade experience.

| Level | Effect |
|:---|:---|
| **Easy** | Slower ghosts, longer power pellet timer |
| **Normal** | Balanced baseline |
| **Hard** | Faster ghosts, shorter power pellet timer |

---

## 👥 Developers

Team members of **BUP CSE - 4**:

- **Md. Udoy Hossain Joy**
- **Imtiyaz Ali**
- **S M Junaed Ahamed Jimon**

---

## 📄 License

This project was developed for academic purposes as part of **BUP CSE - 4**.

All rights reserved by the development team.

---

<p align="center">
  <b>👾 PAC-MAN CLASSIC ARCADE EDITION</b>
  <br>
  <i>PLAY • EAT • SURVIVE</i>
  <br><br>
  Made with ❤️ by BUP CSE - 4
</p>
