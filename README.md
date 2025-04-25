# 👾 Pac-Man Game – 8086 Assembly (MASM615)

A multi-level Pac-Man game developed in **8086 Assembly Language** using **MASM615** using **Irvine Library**

---

## 🎮 Project Highlights

- Developed in **MASM615** (Assembly language)
- 3 Levels with unique layouts and challenges
- AI-based Ghost Movement (Level-wise complexity)
- Player power-ups and collectibles
- Sound effects and screen transitions
- Score system with file handling
- Welcome, Pause, Game Over, and Score screens
- Stack-based procedure calls with `PUSH`/`POP` parameter passing

---

## 🗺️ Game Levels

### Level 1 – *The Beginning*
- Simple maze for learning controls
- Basic ghost chasing behavior
- No power pellets
- Objective: Eat all dots, avoid ghosts

### Level 2 – *The Challenge*
- More complex maze and fruit bonuses
- Ghosts cut off paths (Pinky AI)
- Power pellets allow ghost eating for 20s
- Score bonuses and ghost resets

### Level 3 – *The Showdown*
- Teleports, hidden paths, and boss ghost
- Advanced ghost coordination (Inky & Clyde)
- Cherry bonus adds extra life
- High score potential

---

## 💾 File Handling

- Stores **player names** and **scores** in sorted order
- Ensures scores persist between sessions

---

## 🎨 Screens & UI

You should implement the following screens:
- Welcome screen (takes name input)
- Game menu (Play, Instructions, High Scores)
- Main game screen with player/ghost movement
- Pause screen with resume/exit
- Game over screen
- High scores (Sorted view from file)

---

## 🔊 Sound Features

- Play background music and effects using Irvine32
- Events: dot collected, ghost eaten, game over, life lost, bonus earned

---

## 🚀 How to Run

1. Clone this repo or extract the `.zip` file.
2. Set up your Visual Studio for x86 assembly
3. Import Irvine Library
4. Paste the pacman.asm in your visual studio






