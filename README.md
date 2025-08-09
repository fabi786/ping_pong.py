
# 🕹️ 2-Player Paddle Game (Pong Clone)

This is a simple 2-player Pong-style game built using Python's `turtle` graphics module. Players control paddles to bounce the ball and score points. It includes basic physics, scoring logic, and keyboard interaction.

---

## 🚀 Features

- Two-player gameplay using keyboard controls
- Real-time ball movement and paddle collision detection
- Live score tracking and display
- Bounce sound effects using system audio
- Simple and clean interface

---

## 🎮 Controls

- **Player A**:  
  - Move Up: `W`  
  - Move Down: `S`

- **Player B**:  
  - Move Up: `Up Arrow`  
  - Move Down: `Down Arrow`

---

## 🛠️ Requirements

- Python 3.x  
- No external libraries required (uses built-in `turtle` and `os`)

> 💡 For sound to work, make sure you have a file named `bounce.wav` in the same directory, and your OS supports the `afplay` command (MacOS). You can replace `afplay` with other commands like `start`, `aplay`, or `play` based on your OS.

---

## 📦 How to Run

1. Clone or download this repository.
2. Make sure `bounce.wav` is present in the same folder.
3. Run the script using:

```bash
python game.py
