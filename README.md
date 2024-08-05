## Tic-Tac-Toe - 廣東話版井字過三關

This is a simple Tic-Tac-Toe game implemented in Python using the Tkinter library.  The game allows two players to compete against each other, with the option to input their names. The game interface and messages are displayed in Cantonese.

### How to Play

1. **Run the Python script:**
   - Make sure you have Python installed on your system.
   - Open a terminal or command prompt and navigate to the directory where the script is saved.
   - Run the script using `python tic_tac_toe.py`.

2. **Enter Player Names:**
   - You will be prompted to enter the names for Player 1 and Player 2.

3. **Play the Game:**
   - The game board will appear with buttons representing each cell.
   - Click on a button to place your mark (X or O).
   - The game will automatically switch turns between the players.

4. **Winning and Drawing:**
   - The first player to get three of their marks in a row, column, or diagonal wins the game.
   - If all cells are filled without a winner, the game ends in a draw.

### Features

- **Cantonese Interface:** All text and messages are displayed in Cantonese.
- **Player Name Input:** Allows players to enter their names for a more personalized experience.
- **Simple and Intuitive Gameplay:** Easy to understand and play.

### Code Structure

The code is organized into a `TicTacToe` class, which handles all aspects of the game:

- **`__init__`:** Initializes the game, gets player names, sets up the board, and creates the game interface.
- **`create_widgets`:** Creates the buttons for the game board and the label to display the current turn.
- **`make_move`:** Handles player moves, updates the board, checks for wins and draws, and switches turns.
- **`switch_player`:** Switches the current player.
- **`check_win`:** Checks if a player has won the game.
- **`is_board_full`:** Checks if the board is full (indicating a draw).

### Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or improvements, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the LICENSE file for details.
