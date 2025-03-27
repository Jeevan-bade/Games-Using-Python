
# Pong Game

A classic Pong game implementation using Python's Turtle graphics library.

## Features

- Two-player gameplay (one on each side)
- Score tracking for both players
- Paddle controls:
  - Left player: W (up) and S (down) keys
  - Right player: Up and Down arrow keys
- Ball physics with bouncing off walls and paddles
- Increasing ball speed after each paddle hit
- Score reset when a player misses the ball

## Files

- `main.py`: Main game loop and setup
- `paddle.py`: Paddle class implementation
- `ball.py`: Ball class with movement and bouncing logic
- `scoreboard.py`: Score tracking and display

## Requirements

- Python 3.x
- Turtle module (comes with standard Python installation)

## How to Run

1. Clone the repository or download all the Python files
2. Run the `main.py` file:
   ```
   python main.py
   ```
3. Use the controls to play the game:
   - Left player: W (up), S (down)
   - Right player: Up/Down arrow keys

## Game Rules

- Each time a player misses the ball, the opponent scores a point
- The ball speeds up slightly after each paddle hit
- First player to reach an arbitrary score wins (no win condition implemented, plays indefinitely)

Enjoy the game!
