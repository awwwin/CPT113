# Tic-Tac-Toe Game 
## Description of the game 

Tic Tac Toe is a classic text-based game played on a grid consisting of nine cells. Two players take turns placing their respective symbols (usually "X" and "O") in empty cells with the goal of getting three of their symbols in a horizontal, vertical, or diagonal row. The game starts with an empty grid, and players input their moves by specifying the row and column where they want to place their symbol. The game continues until one player achieves the winning condition or all cells are filled, resulting in a draw. Tic Tac Toe is a simple yet strategic game that requires players to plan their moves and anticipate their opponent's moves to secure a victory.


## Features of the game 

1) Grid: The game is played on a 3x3 grid, although variations with larger grids are also possible.
2) Symbols: The two players are typically assigned different symbols, such as "X" and "O," to mark their moves on the grid.
3) Turn-based Gameplay: Players take turns placing their symbols on the grid. The game enforces alternating turns between the players.
4) Input Validation: The game validates the player's input to ensure they choose a valid and unoccupied cell on the grid.
5) Winning Conditions: The game checks for winning conditions after each move to determine if a player has achieved a winning combination of symbols. This typically includes checking for three symbols in a row, column, or diagonal.
6) Draw Condition: If all cells on the grid are filled and no player has achieved a winning condition, the game ends in a draw.
7) Game State Management: The game keeps track of the current state, including the grid layout and the player's turn.
8) Replayability: After the game ends, players are often given the option to play again, resetting the grid and allowing for a new round.

## How to play the game 

To play Tic Tac Toe, two players take turns marking empty cells on a 3x3 grid with their respective symbols (typically "X" and "O"). The goal is to form a line of three of your symbols either horizontally, vertically, or diagonally. Players must choose an empty cell by specifying the row and column number. The game continues until one player achieves a winning combination, or if all cells are filled without a winner, resulting in a draw. The players should strategize to block their opponent's moves while aiming to create their own winning lines


## Object oriented concept & implementation of linked lists/stacks/queues in the game

* In the Tic Tac Toe game, the object-oriented concept is implemented by defining classes to represent the game components. The game board can be represented as a class, which contains a grid of cells. Each cell can be an object with properties like its position and current symbol. Additionally, a Player class can be defined to represent the players, with attributes such as their name and symbol. The game logic can be encapsulated within a Game class, which handles the player turns, checks for winning conditions, and updates the board accordingly. By using classes, objects, and encapsulation, the Tic Tac Toe game can be structured and organized, promoting code reusability and modularity.

* In the Tic Tac Toe game implementation, the linked list is used to store and manage the history of game moves. The linked list is represented by a private nested struct called Node, which contains the move number and the game board state as its members. The head pointer points to the first node in the list. When a player makes a move, a new node is created and its fields are filled with the current move number and the updated game board state. The nextPtr of the new node is then set to point to the previous head of the list, and the head pointer is updated to point to the new node, effectively adding the new move to the beginning of the list. The displayList function traverses the linked list, starting from the head, and displays the move number and game board state of each node. This allows the players to see the history of moves during the game. Overall, the linked list provides a way to store and access the game board states in a sequential manner, preserving the order of moves and allowing for easy traversal and display of the game history

## Screenshot of TicTacToe 
![Screenshot (205)](https://github.com/awwwin/CPT113/assets/137647370/3a569ff6-99f0-4ada-8d49-7c15386e77c2)

