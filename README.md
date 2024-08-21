![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=Python%20Tic%20Tac%20Toe%20Project&message=Intermediate%20Level&color=7d93a6&style=for-the-badge)

# Python Tic Tac Toe Project

### Application Overview:

The Tic-Tac-Toe application is a simple yet interactive game implemented using Python's Tkinter library. It allows two players to play the classic Tic-Tac-Toe game on a 3x3 grid. The application provides a graphical user interface (GUI) where players can click on buttons representing the grid cells to place their marks (X or O), depending on whose turn it is. The game tracks the players' scores and displays the winner after each round. If all the cells are filled without a winner, the game declares a draw.

### Business Rules:

Player Turns:

The game alternates turns between two players: Player 1 (X) and Player 2 (O). Player 1 always starts the game.
The current player’s mark (X or O) is placed on the grid cell they select.
Grid Update and Validation:

Each grid cell corresponds to a button in the GUI. When a player clicks a button, it is marked with their respective symbol (X or O), and the button is disabled to prevent further clicks.
After each move, the application checks for a winning combination or a draw.
Winning Conditions:

A player wins if they manage to place three of their marks in a horizontal, vertical, or diagonal row.
The game immediately ends after a win, and the winning player’s score is incremented.
Draw Condition:

If all grid cells are filled and no player has achieved a winning combination, the game declares a draw.
Score Tracking:

The application tracks the score for both players. The score is displayed at the top of the application, with Player 1’s score on the left and Player 2’s score on the right.
Game Reset:

After a round (win or draw), the grid is reset for a new game, but the players' scores are retained.
The game can be restarted multiple times, and the scores will continue to accumulate.
Application Flow:

Players take turns clicking on the grid to place their mark.
The application checks for a winner after each move. If a winner is found, the round ends, and the score is updated.
If no winner is found and the grid is full, the round ends in a draw.
After the round, the grid is reset, and players can start a new game with their current scores.
Issues and Considerations:

The game currently has a potential issue with the exit function freezing the application, which needs to be resolved to ensure smooth operation.
The application can be enhanced by adding features such as a more sophisticated scoring system, additional game modes, or AI opponents.
