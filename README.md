Snake Game
A classic Snake game implemented in Python using the Turtle graphics library.

Description
This project recreates the nostalgic Snake game where the player controls a snake to eat food and grow longer, while avoiding collisions with walls and its own tail.

Features
Snake Movement: Control the snake using arrow keys (Up, Down, Left, Right)

Food Collection: Eat the blue food dots to grow longer and increase score

Score Tracking: Real-time score display at the top of the screen

Collision Detection: Game ends if snake hits wall or its own tail

Game Over Screen: Shows final score when game ends

Files
main.py: Main game loop and setup

snake.py: Snake class implementation (movement, growth, controls)

food.py: Food class implementation (random positioning)

scoreboard.py: Score tracking and display

Requirements
Python 3.x

Turtle module (comes with standard Python installation)

How to Run
Clone the repository or download the files

Run main.py using Python:

Copy
python main.py
Use arrow keys to control the snake

Try to get the highest score without crashing!

Controls
Up Arrow: Move snake upwards

Down Arrow: Move snake downwards

Left Arrow: Move snake to the left

Right Arrow: Move snake to the right

Game Rules
Each food collected increases your score by 1 and makes the snake longer

Game ends if:

Snake hits the wall

Snake hits its own tail

Higher difficulty as snake grows longer

Customization
You can easily modify:

Game speed by changing the time.sleep() value in main.py

Screen size by modifying the screen.setup() parameters

Snake and food colors in their respective class file
