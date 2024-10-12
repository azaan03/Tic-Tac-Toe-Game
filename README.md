# Tic Tac Toe Game

## Description
Tic Tac Toe is a classic two-player game where players take turns marking a 3x3 grid with their symbols (X or O). The goal is to place three of your marks in a row, column, or diagonal before your opponent does.

This project features a simple command-line interface where players can input their moves by selecting numbered positions on the grid. The game checks for win conditions after each turn and announces the winner when applicable.

## Features
- Two-player mode
- Interactive command-line interface
- Automatic win detection

## How to Play
1. Clone the repository:
   ```bash
   git clone https://github.com/azaan03/tic-tac-toe.git
   cd tic-tac-toe
   ```

2. Run the game:
   ```bash
   python tic_tac_toe.py
   ```

3. Players take turns entering the number corresponding to the grid position where they want to place their mark:
   - Positions are numbered from 0 to 8, as follows:
     ```
     0 | 1 | 2
     ---------
     3 | 4 | 5
     ---------
     6 | 7 | 8
     ```

4. The game will announce the winner when a player successfully places three of their marks in a row, column, or diagonal.

## Code Explanation
- `sum(a, b, c)`: Helper function that returns the sum of three values, used to check win conditions.
- `printboard(xstate, ystate)`: Displays the current state of the game board.
- `checkwin(xstate, ystate)`: Checks if either player has won the game.
- The main loop allows players to take turns until a win condition is met or the board is filled.

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

