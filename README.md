# 🏓 Ping Pong Game (Python + Kivy)

A simple and interactive Ping Pong game built using **Python** and the **Kivy** framework. This project demonstrates the basics of game development, including animations, collision detection, keyboard controls, and score tracking.

---

## Features

- 🎮 Two-player gameplay
- 🏓 Smooth paddle movement
- ⚽ Ball collision with paddles and walls
- 📊 Real-time score tracking
- 🔄 Ball resets after each point
- 💻 Cross-platform support via Kivy

---

## Technologies Used

- **Python 3.x**
- **Kivy**

---

## Project Structure

```
ping-pong/
│
├── main.py          # Main application entry point
├── myach.kv          # Kivy UI layout
├── README.md        # Project documentation
└── assets/          # Images, sounds (optional)
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/quantum-alien/ping-pong.git
cd ping-pong
```

### 2. Create a virtual environment (optional but recommended)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install kivy
```

or

```bash
pip install -r requirements.txt
```

---

## Running the Game

```bash
python main.py
```

---

## Controls

| Player | Move Up | Move Down |
|---------|---------|-----------|
| Left Paddle | W | S |
| Right Paddle | ↑ | ↓ |

---

## Game Rules

- The ball starts from the center of the screen.
- Players control paddles to keep the ball in play.
- If a player misses the ball, the opponent scores one point.
- The ball resets after each score.
- Keep playing to achieve the highest score!

---

## Requirements

- Python 3.8+
- Kivy 2.x

---

## Future Improvements

- Single-player mode with AI
- Main menu
- Pause and resume
- Sound effects and background music
- Difficulty levels
- Power-ups
- Mobile support

---

---

## Learning Objectives

This project demonstrates:

- Kivy widgets and layouts
- Canvas drawing
- Object movement
- Collision detection
- Keyboard event handling
- Game loop implementation
- Basic game physics

---

---

## Author

Developed by Alien with ❤️ using **Python** and **Kivy**.
