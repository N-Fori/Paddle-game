# 🕹️ Pong Game in Python

This is a classic **Pong** game clone built using Python's `turtle` module.  
Two players can control paddles and try to bounce the ball back and forth. The first to miss gives a point to the opponent.

---

## 🎮 Gameplay

- Player 1 (Left Paddle):  
  - Move Up: `W`  
  - Move Down: `S`

- Player 2 (Right Paddle):  
  - Move Up: `↑`  
  - Move Down: `↓`

- The ball bounces off the top and bottom walls and paddles.
- If a player misses the ball, the opponent scores a point.
- The scoreboard updates after each point.

---

## 🧠 Features

- Smooth paddle and ball animation
- Ball speed increases after each paddle hit
- Score tracking for both players
- Reset ball to center after each point

---

## ▶️ How to Run

1. Make sure Python 3.x is installed.
2. Clone the repository or copy the files:
   - `main.py`
   - `paddle.py`
   - `ball.py`
   - `scoreboard.py`
3. Run the main script:

```bash
python main.py

Project Structure

pong-game/
│
├── main.py            # Main game loop and setup
├── paddle.py          # Paddle class
├── ball.py            # Ball behavior
└── scoreboard.py      # Score tracking and display

Dependencies
Python standard library:

turtle

time

random

No external packages required.

Author
Nándor Forgó
📧 Email: nfori.coding@gmail.com

