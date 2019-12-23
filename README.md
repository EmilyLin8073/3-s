# 3-s
3’s is a multiple player die game where the player with the least points wins. 
It is played with 5 dice. Each player rolls all 5 dice at the same time. 
Each player must take at least one dice each turn but can take more than one. 
The number show on the dice taken will be added to the total points of the player. 
After the player takes the dice that they want, they must roll the remaining dice 
and repeat the process of taking one or more dice until there are no more dice to roll.
If the number shown on a dice is a 3, then that dice is worth zero points. 
This means that the lowest number of points a player can get is zero, given that the 
player rolls a 3 on every single dice by the end of their turn. 
The goal of each player is to beat the player with the least amount of points accumulated.

Using Node.js and the HTTP module in Node.js I create the server and client connections along 
with creating the GUI. 
For the GUI on the server side we will create a text box that shows the players connected or 
if waiting for player to connect. It will also show the players and how many points each player 
currently has.
The client side of the GUI will display the score and player to beat, the player’s own score, 
and the die being rolled. Each client will be able to see the die being rolled and taken even if 
it is not their turn. 
The client will also have a button to roll the die and one to quit. 
If a player decides to quit in the middle of the game then that client will disappear but the game will continue.

