

Breakout Game in Python (Pygame)

This is a simple Breakout Game built using Python and Pygame.
The player controls a paddle to bounce the ball and break all the bricks.
If the ball falls below the paddle, the game is over.
If all bricks are destroyed, you win.

 Requirements

Python 3.x

Pygame

Install pygame using:

pip install pygame


(Activate your virtual environment before installing.)

▶ How to Run
python breakout.py

Controls

⬅ Left Arrow – Move paddle left

➡ Right Arrow – Move paddle right

 Game Features

Brick wall with 10 columns and 6 rows

Paddle movement

Ball collision with:

Walls

Paddle

Bricks

Sound effects:

bounce.wav for paddle hit

hit.wav for brick hit

Win and Game Over screens

Project Structure
Breakout_Python_game/
│
├── breakout.py
├── bounce.wav
├── hit.wav
├── README.md
├── .gitignore
└── venv/

Concepts Used

Object Oriented Programming (Classes: Brick, Paddle, Ball)

Collision Detection

Game Loop

Keyboard Input

Sound Handling

Frame Control (FPS)

Author

Vigneshwaran
Python Game Development Practice Project 🎮
GitHub: https://github.com/Vignesh3447
