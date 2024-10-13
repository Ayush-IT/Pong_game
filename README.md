# Pong_game

Pong Game
This is a simple Pong game built using Python's Turtle module. The game simulates a two-player version of Pong, with paddles on each side of the screen, a ball that bounces between the paddles, and a scoreboard to keep track of the players' scores.

Features
Two-player paddle controls (left and right paddles)
Ball movement and bouncing logic
Scoreboard to track points for each player
Adjustable ball speed based on gameplay events
Project Structure
The project consists of the following Python files:

main.py: This is the main game loop where all objects (screen, paddles, ball, scoreboard) are initialized, and the game runs.
paddle.py: Contains the Paddle class to control the movement of the paddles.
ball.py: Contains the Ball class that handles ball movement and bouncing logic.
scoreboard.py: Contains the Scoreboard class to display and update the players' scores.
Gameplay Instructions
Player Controls:

Left Paddle (Player 1): Use the W key to move up and the S key to move down.
Right Paddle (Player 2): Use the Up Arrow to move up and the Down Arrow to move down.
The game starts with the ball moving in a random direction. The goal is to prevent the ball from passing your paddle by blocking it with the paddle. If the ball passes a player's paddle, the opponent scores a point.

The game will continue indefinitely until closed.


Dependencies
This project uses the built-in Turtle module from Python, so no external libraries are required.
