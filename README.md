# Tetris – C++ Game with Graphics and Scoring

A complete Tetris clone written in **modern C++**, featuring a graphical interface, real-time controls, score tracking, level progression, and persistent high scores.  
The project applies object-oriented design to model game components cleanly and is structured for readability, modularity, and extensibility.

---

## Features

- **Graphical game board**  
  Real-time rendering of the board and tetrominoes with visual feedback.

- **Keyboard-based player control**  
  Move, rotate, and drop pieces with smooth, responsive input.

- **Game progression and scoring**  
  - Automatic line clearing  
  - Scoring system with increasing speed by level  
  - Game over detection and feedback  

- **High score tracking**  
  Stores best scores persistently across sessions.

- **Menu system and multiple modes**  
  Choose between standard gameplay or test mode using input files for automated runs.

- **File-based test support**  
  Optional input files to preload tetromino sequences and scripted movements.

---

## Controls

<div align="center">

| Key         | Action                        |
|-------------|-------------------------------|
| ← / →       | Move piece left / right       |
| ↑           | Rotate clockwise              |
| ↓           | Rotate counter-clockwise      |
| `Space`     | Hard drop                     |
| `Esc`       | Exit the game                 |

</div>

---

## Class Structure

<div align="center">

| Class      | Description                                  |
|------------|----------------------------------------------|
| `Tetris`   | Main application and menu system             |
| `Partida`  | Game session controller (board, score, speed)|
| `Tauler`   | Board state and collision logic              |
| `Figura`   | Tetromino representation and rotation        |
| `InfoJoc`  | Shared enums and game constants              |

</div>

---

## Build & Run

### Requirements

- C++11 or newer  
- SDL2 or compatible graphics library  
- CMake or Make  

---

## Screenshots

### Main Menu

<div align="center">
  <img width="302" height="150" alt="Captura de pantalla 2025-07-17 153936" src="https://github.com/user-attachments/assets/5f469f39-cd6d-4359-ae33-d3115ad5e976" />
</div>

---

### In-Game 

<div align="center">
  <img width="678" height="817" alt="Captura de pantalla 2025-07-17 154449" src="https://github.com/user-attachments/assets/90016ac9-f184-49b9-b118-7e6230e360e5" />
</div>

---

### High Scores Screen

<div align="center">
  <img width="174" height="125" alt="Captura de pantalla 2025-07-17 154605" src="https://github.com/user-attachments/assets/b6db3268-a3b8-477e-bd4c-f5a6330389ad" />
</div>

