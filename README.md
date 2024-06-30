# Python-projects
currently there are 4 projects in this repository.
1) dice roll simulator - it uses random library of python to get a number between 1 and 6 and ask the user if they want to roll it again or not.
2) random password generator- this also uses the random library to generate a password of specified length.it first ask the user to specify the desired length of password then generate a random password of that length random letters are generated from a alphanumeric string.
3) guess a number - this also uses random library to generate a random number and then gives the user 3 chances to guess the right answer.
4) snake game-
   This is a simple implementation of the classic Snake game using Python's Turtle graphics library. Control the snake to eat food, grow in length, and avoid self-collision.

Requirements
Python 3.x
How to Run
Save the code in a file (e.g., snake_game.py).
Run the game with:
bash
Copy code
python snake_game.py
Controls
Arrow keys to control the snake.
Code Overview
Constants: Define screen size, food size, delay, and movement offsets.
Functions:
reset(): Resets game state.
move_snake(): Moves the snake, checks collisions, handles wrapping, and updates the screen.
food_collision(): Checks if the snake eats the food and places new food.
get_random_food_pos(): Generates a random position for food.
get_distance(pos1, pos2): Calculates distance between two points.
Direction functions (go_up(), go_right(), go_down(), go_left()): Change snake's direction.
Setup:
Initializes the screen and event handlers.
Creates turtle objects for the snake and food.
Game Loop: Starts with reset() and repeatedly calls move_snake() using turtle.ontimer.
Enjoy the game!
