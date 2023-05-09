# Tic Tac Toe

This is a Java implementation of the classic Tic Tac Toe game. It uses a 3x3 board and two players who take turns marking the board with their respective marks (X or O). The first player to get three marks in a row (horizontally, vertically, or diagonally) wins the game. If all spaces on the board are filled and no player has won, the game ends in a draw.

## How to Play

To play the game, simply run the `TicTacToe` class. The game will start and prompt the players to take turns entering row and column numbers to place their marks on the board. Players can only place their mark on a space that is currently empty. Once a player wins or the board is full, the game ends and displays the winner or a draw message.

## Implementation Details

The game is implemented using object-oriented programming principles in Java. The `TicTacToe` class represents the game itself, while the `board` array holds the current state of the board. The class also contains methods for initializing the board, printing the board, checking for a win, changing the current player, and placing a mark on the board. 

The game uses a `Scanner` object to get input from the players via the console. The game loop continues until either a player wins or the board is full. During each iteration of the loop, the board is printed, the current player is prompted to enter their move, and the move is validated and placed on the board. If a player wins, the game loop ends and displays the winner. If the board is full and no player has won, the game ends and displays a draw message.

## Future Improvements

Possible improvements for this implementation of Tic Tac Toe include:

- Adding a graphical user interface (GUI) to make the game more visually appealing and user-friendly.
- Implementing an artificial intelligence (AI) opponent to play against the user.
- Allowing the user to choose the board size, such as 4x4 or 5x5, to increase the difficulty and variability of the game.

## Contributing

This program was created as a learning exercise and is not intended for production use. However, if you would like to contribute to the project, feel free to submit a pull request.

## License

This project is released under the MIT license. See the `LICENSE` file for more information.
