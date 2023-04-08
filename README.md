# TicTacToe_Java
A simple TicTacToe game I made on Java using the IDE BlueJ in 10th grade. It has very basic GUI but required a decent foundational understanding of the logic behind detection of the winner in the game.
The .java files include the lines of code used to create this game.
TicTacToeWelcome class is used to initialize the welcome page and other GUI elements used in it. It also links with the TicTacToe Game class.
TicTacToeGame class initializes the grid and links back to the TicTacToeWelcome class. It has GUI elements like buttons for inputting your choice i.e. X or O. It calls functions for buttons like play again exit and user inputs.
MemoryBoard is a class which forms the backbone of this game and this is the backend part of the game. It has functions with logic for the game to detect winner after every turn and if there is none, to keep the game going. It stores the position of every X and O as well to find out the winner.
