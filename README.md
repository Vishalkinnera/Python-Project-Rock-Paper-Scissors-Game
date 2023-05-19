# Rock-Paper-Scissors-Game-Project

This is the step-by-step explanation of what is happening in the code:

1) It imports the random module, which allows generating random numbers.
2) The game rules are printed, explaining the possible outcomes of each choice.
3) The code enters a while loop, which continues until the player decides to stop playing.
4) Inside the loop, the user is prompted to enter their choice by selecting a number between 1 and 3, representing Rock, Paper, or Scissors, respectively.
5) If the user enters an invalid choice, they are asked to enter a valid choice.
6) The user's choice is stored and displayed.
7) The computer's choice is generated randomly using the random.randint() function. The computer selects a number between 1 and 3, representing its choice of Rock, Paper, or Scissors.
8) If the computer's choice happens to be the same as the user's choice, the computer reselects until they are different.
9) The computer's choice is stored and displayed.
10) The comparison between the user's choice and the computer's choice is performed to determine the winner.
11) If the choices are the same, it's a draw. Otherwise, the conditions for winning are checked, and the winner is determined based on the game rules.
12) The result of the game is displayed.
13) The user is asked if they want to play again. If the answer is 'n', the loop breaks, and the game ends. Otherwise, the loop continues, and a new round begins.
14) After exiting the loop, a "thank you" message is printed, indicating the end of the game.
