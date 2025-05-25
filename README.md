# 🐍 Snake Game in Python using Turtle

A fun and interactive **Snake Game** built using Python's `turtle` module. This project is a recreation of the classic snake game where the player controls a growing snake that must avoid walls and its own tail while collecting food.

---

## 📸 Demo

![Snake Game Demo](snake-game-demo.gif)

---

## 🛠️ Technologies Used

- **Python 3**
- **Turtle** (for graphics and game display)
- **Random** (to randomize food position and color)
- **Time** (for game loop delay and speed control)

---

## 🎮 How to Play

- Use `W`, `A`, `S`, `D` keys to control the direction of the snake:
  - `W` → Up
  - `S` → Down
  - `A` → Left
  - `D` → Right
- Eat the food to grow your snake and increase your score.
- Avoid hitting the walls or your own tail — or the game resets.
- Your **High Score** is tracked throughout the game session.

---

## 📂 Features

- Real-time snake movement and keyboard input
- Random food colors and positions
- Dynamic score and high score tracking
- Game over and restart logic
- Body segment movement and growth
- Clean and readable code structure

---

## 🧠 Concepts and Operators Used

- **Modules:** `turtle`, `random`, `time`
- **Data Structures:** `list` (to store snake segments)
- **Control Structures:** `if`, `else`, `while`
- **Functions:** for modular and reusable code
- **Keyboard Events:** `onkeypress` with `listen`
- **Collision Detection:** using `distance()` and boundary limits
- **String Formatting:** `str.format()` for score display

---

## 📘 What I Learned

- How to use Python’s built-in `turtle` module to create simple graphics and animations
- Managing game logic using infinite loops and delay control
- Writing clean, modular code using functions
- Real-time event handling using keyboard input
- Collision detection and list management for game mechanics

---

## 🚀 Getting Started

### ✅ Requirements

- Python 3.x installed on your system

### ▶️ Run the Game

```bash
python snake_game.py
