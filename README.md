





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
| <!-- Main Menu --> <img width="918" height="808" alt="Screenshot 2026-10-20 232826" src="https://github.com/user-attachments/assets/71d11b2e-30dd-44b3-bb11-65eb6562f643" /> | <!-- Map Selection --> <img width="917" height="807" alt="Screenshot 2026-10-20 232852" src="https://github.com/user-attachments/assets/1a719fcd-a87d-465e-8669-16347af197b8" /> |

| Leaderboard | Developers / About Us |
| :---: | :---: |
| <!-- Leaderboard --> <img width="919" height="808" alt="Screenshot 2026-10-20 232841" src="https://github.com/user-attachments/assets/b8746106-9a4c-4ab6-bdd1-230f73ed41d9" /> | <!-- About Us --> <img width="919" height="808" alt="Screenshot 2026-10-20 233907" src="https://github.com/user-attachments/assets/e6bc3b47-fabc-42e7-b082-e328f8637f17" /> |

| How To Play | Exit Confirmation |
| :---: | :---: |
| <!-- How To Play --> <img width="919" height="809" alt="Screenshot 2026-10-20 233854" src="https://github.com/user-attachments/assets/9196865b-4a25-42d2-861b-86d024760ed0" /> | <!-- Exit Game --> <img width="920" height="809" alt="Screenshot 2026-10-20 233915" src="https://github.com/user-attachments/assets/1de3ef80-7f9c-48ce-bc6b-aee2f92c91ec" /> |

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
