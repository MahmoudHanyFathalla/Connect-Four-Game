# Connect Four Game

## Overview
This is a simple Python implementation of the classic **Connect Four** game. It allows two players to take turns inserting their pieces into a vertical grid, aiming to connect four of their pieces in a row, column, or diagonal.

## Features
- Two-player gameplay (Red vs. Yellow)
- Dynamic board creation with customizable columns and rows
- Checks for a winner after each move
- Supports vertical, horizontal, and diagonal wins
- Simple text-based interface

## How to Play
1. Run the script.
2. Players take turns entering the column number where they want to drop their piece.
3. The game checks for a winner after every move.
4. The first player to connect four pieces in a row, column, or diagonal wins.

## Installation
No external dependencies are required. Simply run the script with Python:

```sh
python connect_four.py
```

## Code Structure
- `Game` class: Handles the game logic and board management.
- `insert(column, color)`: Inserts a piece into the specified column.
- `checkForWin()`: Checks if a player has won after each move.
- `getWinner()`: Determines the winner by checking all possible winning conditions.
- `printBoard()`: Prints the current state of the board.

## Example Gameplay
```
0  1  2  3  4  5  6
.  .  .  .  .  .  .
.  .  .  .  .  .  .
.  .  .  .  .  .  .
.  .  .  .  .  .  .
.  .  .  .  .  .  .
.  .  .  .  .  .  .
Red's turn: 3
```

## Customization
You can change the board size and required number of connections to win by modifying the `Game` class initialization:

```python
g = Game(cols=7, rows=6, requiredToWin=4)
```

## License
This project is licensed under the MIT License.

