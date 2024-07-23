# Tic Tac Toe Project

## Overview
This project implements a simple text-based version of the classic game Tic Tac Toe. The game allows two players to play against each other in a turn-based manner. The project focuses on practicing Python programming concepts such as functions, loops, and conditionals.

## Project Steps
### Step 1: Board Display
- Write a function that can print out a board.
- The board is set up as a list, where each index 1-9 corresponds with a number on a number pad, resulting in a 3 by 3 board representation.

### Step 2: Player Input
- Write a function that can take in a player's input and assign their marker as 'X' or 'O'.
- Use while loops to continually ask for the input until you get a correct answer.

### Step 3: Place Marker
- Write a function to place a marker on the board at the desired position.
- Test the function using test parameters and display the modified board.

### Step 4: Win Check
- Write a function that takes in a board and a mark (X or O) and checks if that mark has won.
- Test the win_check function against a test board to ensure it returns True when a player has won.

### Step 5: Randomly Choose First Player
- Write a function that uses the random module to randomly decide which player goes first.
- Return a string indicating which player goes first.

### Step 6: Check for Free Space
- Write a function that returns a boolean indicating whether a space on the board is freely available.

### Step 7: Check if Board is Full
- Write a function that checks if the board is full and returns a boolean value. True if full, False otherwise.

### Step 8: Player's Next Position
- Write a function that asks for a player's next position (as a number 1-9).
- Use the function from Step 6 to check if it's a free position. If it is, return the position for later use.

### Step 9: Play Again
- Write a function that asks the player if they want to play again and returns a boolean True if they do.

### Step 10: Run the Game
- Use while loops and the functions created in the previous steps to run the game, allowing two players to play against each other.

## Technologies and Tools
- Python for the implementation of the game logic.

## Repository Structure
- `notebooks/`: Jupyter notebook with the implementation of the game.
- `README.md`: Project overview and documentation.

## How to Run the Project
1. Clone the repository.
2. Install the required dependencies (if any).
3. Run the Jupyter notebook in the `notebooks/` directory to play the game.

## Contact
For any questions or collaboration opportunities, feel free to reach out.
