# Rock-Paper-Scissors-Game-Using-Python
Rock Paper Scissors Game
This project is a Rock Paper Scissors game that allows users to play against the computer. The game follows the classic rules, and the winner is determined based on the user's and computer's choices.

## How it Works
The program asks the user to:

Choose an option:

1 for Rock
2 for Paper
3 for Scissors
The computer makes a random choice from the same three options.

## The result is printed based on the winning rules:

Rock vs Paper → Paper wins
Rock vs Scissors → Rock wins
Paper vs Scissors → Scissors wins
If both the user and computer make the same choice, it results in a tie.

## Input Requirements
Enter your choice (1 for Rock, 2 for Paper, 3 for Scissors).
If an invalid input is entered, the program asks the user to enter a valid choice.
At the end of the game, the user is asked if they want to play again (Y/N).

## Code Explanation
User and Computer Input
User input is taken through input() and validated to ensure it's within the valid range (1 to 3).
Computer input is generated randomly using random.randint(1, 3).
Determine the Winner
The game logic compares the user’s choice with the computer’s choice and determines the winner based on predefined rules.
Game Loop
The program runs in a while loop, allowing the user to play multiple rounds until they choose to quit by entering 'N' or 'n'.
