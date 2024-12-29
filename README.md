Tic Tac Toe (Python Code)

Description

This is an easy-to-use command-line-based implementation of the popular two-player game Tic Tac Toe in Python. The two players take turns until someone wins or there is no more move to make-the game ends in a draw.

How to Play

The game board is set up as a 3x3 grid, positions numbered from 1 to 9:

 7 | 8 | 9
-----------
 4 | 5 | 6
-----------
 1 | 2 | 3

Player 1 and Player 2 select 'X' or 'O'.

Players take turns to put the marker on the board by selecting a spot (1-9).

If three markers are aligned, the game declares the winner horizontally, vertically, or diagonally.

In case the board becomes full with no winner, then the game ends as a draw.

Features

Game for two interactive players

The game selects the first player randomly

The board is updated in real-time after every move.

It determines the winning moves and declares a winner.

Instruct the user to play the game again after finishing.

Installation

Clone the repository:

git clone https://github.com/Spreddy01/Project1.git

Change into the project directory:

cd Project(1)

Run the game:

python Project(1).py

Requirements

Python 3.x

IPython (Optional, for clear screen functionality)

Install dependencies (if necessary):

pip install IPython

Overview of Code
display_board(): Prints the current state of the board.

player_input(): Asks Player 1 to select his marker ('X' or 'O').

place_marker(): Places a marker at a specific board position.

win_check(): Determines if the current player has won.

choose_first(): Determines randomly which player goes first.

space_check(): Checks if a specific position on the board is available.

full_board_check(): Checks if the board is full.

player_choice(): Prompts the player to choose a position to place their marker.

replay(): Asks if players want to restart the game after completion.

Future Enhancements

Add AI opponent for single-player mode.

Implement GUI using tkinter or Pygame.

Allow custom board sizes.

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Inspired by traditional games of Tic Tac Toe.

This was developed for learning in Python programming.
