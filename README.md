# Tic-Tac-Toe Game 
## Explanation of the game 

The classic text-based game of Tic Tac Toe is played on a grid comprising nine cells. In the game of tic-tac-toe, two players strategically place their symbols, typically "X" and "O," in empty cells with the objective of achieving a sequence of three of their symbols in a row, either horizontally, vertically, or diagonally. In this game, players begin with an empty grid and proceed to input their moves by indicating the desired row and column for symbol placement. In the game, the winning condition or a draw is reached when one player achieves victory or all cells are filled. The game of Tic Tac Toe is characterised by its simplicity and strategic nature, as players must strategically plan their moves and anticipate their opponent's moves in order to achieve a winning outcome.


## The game's features include: 

1) Game board: The game is played on a 3x3 grid, but it is also possible to play variations with larger grids.
2) Symbols: In this game, each player is usually given an individual symbol, like "X" and "O," to indicate their moves on the grid.
3) Turn-based Gameplay: Each player takes turns placing their symbols on the grid. The game requires players to take turns in an alternating style.
4) Input Validation: The game ensures that the player's input is valid by checking if the chosen cell on the grid is both valid and unoccupied.
5) Winning Conditions: After each move, the game checks for winning conditions to determine if a player has achieved a combination of symbols that results in a win. Typically, this involves checking for three symbols in a row, column, or diagonal.
Draw Condition: The game ends in a draw if all cells on the grid are filled and no player has achieved a winning condition.
Game State Management involves keeping track of the current state of the game, which includes the grid layout and the player's turn.
8) Replayability: Once the game concludes, players are frequently presented with the opportunity to play again. This option resets the grid and enables a fresh round to be played.

## Here's a guide on how to play the game. 

In a game of Tic Tac Toe, two players take turns marking empty cells on a 3x3 grid using their respective symbols, usually "X" and "O". The objective is to create a line of three of your symbols, which can be arranged horizontally, vertically, or diagonally. To select a cell, players need to indicate the row and column number of an empty cell. The game will continue until a player achieves a winning combination, or if all cells are filled without a winner, resulting in a draw. To increase their chances of winning, players should focus on strategic moves that not only block their opponent's progress but also aim to create winning lines of their own.


## The game's implementation involves the use of object-oriented concepts for linked lists.

*In the game of Tic Tac Toe, the object-oriented concept is utilised by creating classes that represent the various components of the game. The game board can be represented as a class that contains a grid of cells. Each cell can be represented as an object with properties such as its position and the symbol it currently holds. In addition, we can define a Player class to represent the players. This class can have attributes such as their name and symbol. The game logic can be neatly organised by encapsulating it within a Game class. This class will be responsible for managing player turns, verifying winning conditions, and updating the game board accordingly. The use of classes, objects, and encapsulation in the Tic Tac Toe game allows for a structured and organised approach, enhancing code reusability and modularity.

*The implementation of the Tic Tac Toe game utilises a linked list to effectively store and manage the history of game moves. The linked list is represented by a private nested struct called Node. This struct contains the move number and the game board state as its members. The head pointer indicates the first node in the list. Whenever a player makes a move, a new node is generated. This node contains the current move number and the updated game board state. The nextPtr of the new node is set to point to the previous head of the list. Then, the head pointer is updated to point to the new node. This effectively adds the new move to the beginning of the list. The displayList function loops through the linked list, starting from the head, and displays the move number and game board state of each node. This feature enables players to view the move history throughout the game. The linked list is a useful data structure for storing and accessing game board states in a sequential manner. It preserves the order of moves and allows for easy traversal and display of the game history.


## Screenshot of TicTacToe 
![Screenshot (205)](https://github.com/awwwin/CPT113/assets/137647370/3a569ff6-99f0-4ada-8d49-7c15386e77c2)

## Link demo
