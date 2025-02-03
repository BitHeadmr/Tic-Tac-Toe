The Classic Tic-Tac-Toe Game in Python 
First, let’s see how we are going to use a dictionary to create our game board. A dictionary is a primitive data type in python which stores data in “key: value” format. and thus, we’ll create a dictionary of length 9 and each key will represent a block in the board and its corresponding value will represent the move made by a player. and we’ll create a function printBoard() which we can use every time we want to print the updated board in the game. 
The main function, we’ll first take the input from the player and check if the input is a valid move or not. If the block that player requests to move to is valid, we’ll fill that block else we’ll ask the user to choose another block. 
To check the winning condition, we’ll check a total of 8 conditions and whichever player has made the last move, we’ll declare that player as a winner. And if no one wins, we’ll declare ‘tie’ 

