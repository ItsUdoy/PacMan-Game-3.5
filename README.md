# 👾 Pac-Man Classic Arcade Edition (v3.5)

![Java](https://img.shields.io/badge/Language-Java-orange.svg)
![GUI](https://img.shields.io/badge/GUI-Java%20Swing-blue.svg)
![Architecture](https://img.shields.io/badge/Architecture-Single--File-brightgreen.svg)
![License](https://img.shields.io/badge/License-purple.svg)

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

| Main Menu | Map Selection |
| :---: | :---: |
| <!-- Main Menu --> <img src="https://github.com/user-attachments/assets/baf6e889-ecd4-49ca-91d9-9197826ae722" alt="Main Menu" width="450" /> | <!-- Map Selection --> <img src="https://github.com/user-attachments/assets/4958c672-4507-4594-ba8d-86a40cc6799c" alt="Map Selection" width="450" /> |

| Leaderboard | Developers / About Us |
| :---: | :---: |
| <!-- Leaderboard --> <img src="https://github.com/user-attachments/assets/d5d00d40-0292-4e74-80b9-a8133a8ed8f6" alt="Leaderboard" width="450" /> | <!-- About Us --> <img src="https://github.com/user-attachments/assets/a49b3ce0-6f2a-436b-b155-75e784ee7eab" alt="About Us" width="450" /> |

| How To Play | Exit Confirmation |
| :---: | :---: |
| <!-- How To Play --> <img src="https://github.com/user-attachments/assets/9d985336-edb0-4a29-8b1c-780852663686" alt="How To Play" width="450" /> | <!-- Exit Game --> <img src="https://github.com/user-attachments/assets/ee49961e-2df3-4a82-b937-b344d9ea2623" alt="Exit Game" width="450" /> |

---

## ✨ Key Features

- **🎮 Classic Arcade Gameplay**: Grid-aligned cornering, ghost AI pathfinding, frightened ghost modes, and responsive player movement controls.
- **🗺️ Multiple Selectable Maps**: Three distinct level layouts (see [Maps](#️-maps)).
- **⚡ Dynamic Difficulty**: Play on Easy, Normal, or Hard, affecting ghost baseline speeds and power pellet timers.
- **🏆 Persistent Top 10 Leaderboard**: Uses Java's native `Preferences` API for local score tracking, recording player name, score, map, difficulty, cleared mazes, extra hearts, and completion date.
- **❤️ Extra Life System**: Eating 3 blue ghosts during power food mode grants **+1 Extra Heart** (capped at a maximum of 5 lives).
- **🔊 Synthesised Retro Sound**: Built-in audio generator producing triangle, square, sine, and sawtooth sound effects using the pure `javax.sound.sampled` API (no external MP3/WAV files required).
- **🎨 Pure Retro Aesthetic**: Custom neon glowing borders, retro typography, pixel-art styling, and optional CRT scanline overlay.

---

## 🕹️ Controls

| Key | Action |
| :--- | :--- |
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

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/pacman-arcade-edition.git
   cd pacman-arcade-edition
   ```

2. **Compile the game** (replace `PacManGame.java` with your actual file name):
   ```bash
   javac PacManGame.java
   ```

3. **Run it**:
   ```bash
   java PacManGame
   ```

---

## 🗺️ Maps

| # | Map | Description |
| :-: | :--- | :--- |
| 1 | **NEON ARCADE** | Standard arcade grid |
| 2 | **CSE - 4** | Custom department-themed maze |
| 3 | **ZIGZAG HALLS** | High-density corridor layout |

---

## ⚡ Difficulty Levels

| Level | Effect |
| :--- | :--- |
| **Easy** | Slower ghosts, longer power pellet timer |
| **Normal** | Balanced baseline |
| **Hard** | Faster ghosts, shorter power pellet timer |

---

## 👥 Developers

Team members of **BUP CSE - 4**:

- Md. Udoy Hossain Joy
- Imtiyaz Ali
- S M Junaed Ahamed Jimon

---

## 📄 License

This project was developed for academic purposes as part of **BUP CSE - 4**.
All rights reserved by the development team.
