# TicTacToe
Tic Tac Toe is a simple two-player paper-and-pencil game played on a 3x3 grid. Players take turns marking an empty cell with their symbol, 'X' or 'O.' The objective is to form a horizontal, vertical, or diagonal line of three of their symbols. The first player to achieve this wins. If the grid is filled without a winner, the game ends in a draw. 
Tic Tac Toe Game Description
Objective:
The objective of the Tic Tac Toe game is to be the first player to form a horizontal, vertical, or diagonal line of three of your symbols ('X' or 'O') on the 3x3 grid.

Game Rules:

*The game is played on a 3x3 grid, initially empty.
*Two players participate in the game, one playing as 'X' and the other as 'O'.
*Players take turns to place their symbols on the grid until one player wins or the game ends in a draw.
*The first player to get three of their symbols in a horizontal, vertical, or diagonal row wins the game.
*If all cells on the grid are filled and no player has three in a row, the game ends in a draw.
Game Flow:

The game starts with an empty grid displayed on the screen.

1.Player 'X' goes first, followed by Player 'O', and they take turns until the game ends.

2. Players enter their moves by specifying the row and column they want to mark.
  
3. The game validates the input to ensure it is within the valid range (1 to 3) and that the chosen cell is unoccupied.
   
4. After each move, the grid is updated with the player's symbol, and the game checks if the move resulted in a win or draw.
   
5. If a player wins or the game is a draw, the result is displayed, and players are asked if they want to play again.
   
6. If the players choose to play again, the grid is reset, and a new game begins; otherwise, the program terminates.

Java Implementation:

1.Create a 2D array to represent the game board. Each cell of the array will store the player's symbol ('X' or 'O') or be marked as empty.

2.Implement a TicTacToe class that handles the game logic, such as checking for a win or draw, validating inputs, and updating the board after each move.

3.Create a Player class to keep track of the player's name and the symbol they are using ('X' or 'O').

4.Use a Game class to manage the flow of the game, taking turns for each player, displaying the board, and checking for game results.

5.Consider implementing a separate Main class to run the game and handle user input through the console.

Optional Enhancements:
You can enhance the game by adding additional features such as:

1.A graphical user interface (GUI) using Java's Swing or JavaFX libraries.
2.Implementing different difficulty levels for an AI computer opponent using algorithms like Minimax with Alpha-Beta Pruning.
3.Adding an option to choose the board size for a more challenging experience (e.g., 4x4 or 5x5 grids).
