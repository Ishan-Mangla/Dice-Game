SIMPLE DICE ROLLING GAME

**Description**
This is a simple command-line dice rolling game implemented in Python. The game supports 2 to 4 players, and the first player to reach a score of 50 or more wins the game.
The game simulates rolling a six-sided die, and players take turns rolling the die to accumulate points. Rolling a 1 ends the player's turn, and their score for that turn is reset to zero.

**Features**

1. Multiplayer: Supports 2 to 4 players.
2. Simple Mechanics: Players take turns rolling a die until one reaches the winning score of 50.
3. Randomized Dice Rolls: The game uses Python’s random module to simulate realistic dice rolls.
4. End Turn on 1: Rolling a 1 ends the player's turn and forfeits their points for that turn.
   
**How to Play**

-> Start the Game:

The game prompts the user to enter the number of players (between 2 and 4).

-> Roll the Dice:

During each player's turn, they can choose to roll the dice or pass their turn.
If a player rolls a 1, their turn ends, and they score no points for that turn.
Rolling any number other than 1 adds the rolled value to the player's current score for that turn.

-> End the Turn:

Players can choose to end their turn at any time to lock in their points.

-> Winning the Game:

The game continues until one player reaches a total score of 50 or more.
The player with the highest score when the game ends is declared the winner.

**Code Structure**

-> roll(): Function that simulates rolling a six-sided die and returns a random value between 1 and 6.
-> Main game loop: Handles the logic for multiple players, rolling the dice, and determining the winner.

EXAMPLE

Enter the number of players (2-4): 3

Player number 1 turn has just started!
Your total score is: 0

would you like to roll (y)? y
You rolled a: 5
Your score is: 5
would you like to roll (y)? y
You rolled a: 1
You rolled a 1! Turn done!
Your total score is: 0

Player number 2 turn has just started!
Your total score is: 0

**Requirements**
Python 3.x
