# Dice Game

This is a simple text-based dice game for 2 to 4 players. Players take turns rolling a six-sided die to accumulate points, with the objective of reaching a maximum score of 50 to win the game.

## How to Play

1. Run the script.
2. Enter the number of players (2 - 4) when prompted.
3. Players take turns rolling the dice.
4. Each player's score is displayed after each roll.
5. If a player rolls a 1, their turn ends, and they lose all points accumulated in that turn.
6. Players can choose to roll the dice (enter 'y') or end their turn (enter any other key).
7. The game continues until one player reaches or exceeds a score of 50.

## Code Explanation

The code is written in Python and utilizes the `random` module for rolling the dice and making the game random and unpredictable. Here's a brief overview of how the code works:

- Players are prompted to enter the number of players (between 2 and 4).
- Each player takes turns rolling the dice, accumulating points based on the roll.
- If a player rolls a 1, their turn ends, and they lose their current turn's points.
- Players can choose to continue rolling or end their turn after each roll.
- The game continues until one player reaches or exceeds a score of 50.
- The player with the highest score at that point is declared the winner.

## Running the Code

To run the code, make sure you have Python installed on your system. Then, save the code to a Python file (e.g., `dice_game.py`) and execute it using your preferred Python interpreter.

Have fun playing the dice game, and may the best player win!
