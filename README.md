# 🐍 Snake Game in C++ using SFML

This is a classic **Snake Game** built using **C++** and all **five modules of SFML (Simple and Fast Multimedia Library)**.  
The game includes **file-based score saving**, smooth visuals, and real-time gameplay — built as a project to strengthen my object-oriented programming and game dev skills.

---

## 🚀 Features

- Classic snake gameplay with modern controls
- Score tracking system
- **Player scores saved in a local file**
- Clean and colorful UI with SFML
- Responsive keyboard input and smooth animation

---

## 🛠️ Tech Stack

- **Language:** C++  
- **Graphics Library:** [SFML 2.5+](https://www.sfml-dev.org/)  
- **Platform:** Desktop (Windows/Linux)

---

## 🎮 How to Play

- Use arrow keys to control the snake
- Eat the food to grow and increase your score
- Avoid collisions with walls or your own tail to stay alive!

---

## 💾 Score Saving

Each time a game ends, the player's score is automatically saved to a file (`scores.txt`).  
This allows for persistent score tracking across sessions.

---

## 📦 SFML Modules Used

All five SFML modules are actively used in this project:

| Module        | Usage                                                                 |
|---------------|-----------------------------------------------------------------------|
| `sfml-graphics` | Rendering shapes, text, game elements (snake, food, background)     |
| `sfml-window`   | Creating the game window, handling events like closing or resizing  |
| `sfml-system`   | Managing time (clocks, delays), coordinates, and basic utilities    |
| `sfml-audio`    | Playing background music and sound effects (like eating or dying)   |
| `sfml-network`  | *(Optional or planned)* Placeholder for future online leaderboard or multiplayer |


---

## ⚙️ How to Run

1. **Install SFML**  
   Follow the [SFML setup tutorial](https://www.sfml-dev.org/tutorials/2.5/) for your system.
