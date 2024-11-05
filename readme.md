# Tic-Tac-Toe Game in Python

## Description

This is a command-line Tic-Tac-Toe game implemented in Python. It allows two players to take turns marking cells on a 3x3 board. The game checks for winning conditions across rows, columns, and diagonals, ending when a player wins or the game results in a draw.

## How to Play

1. The game is played on a 3x3 grid, initially empty.
2. Player X starts the game, followed by Player O.
3. Players take turns entering the row and column numbers (1 to 3) to place their symbol in the corresponding cell.
4. If a player successfully places three of their symbols in a row, column, or diagonal, they win.
5. If all nine cells are filled without a winner, the game is a draw.

## Features

- **Two-player mode**: Each player takes turns entering their move.
- **Winner and Draw Detection**: Checks if there’s a winning line or a full board resulting in a draw.
- **Input Validation**: Ensures players enter valid moves and handles incorrect inputs gracefully.

## Code Structure

- `prikazi_tablu(tabla)`: Displays the current board layout.
- `proveri_pobednika(tabla, igrac)`: Checks if the specified player has won by forming a row, column, or diagonal of matching symbols.
- `iks_oks()`: Main game function that handles player turns, input, and game progression.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### How to Run

1. Clone this repository.
2. Open a terminal and navigate to the project directory.
3. Run the game with the following command:

```bash
python tic_tac_toe.py
```
