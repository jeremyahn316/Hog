# Hog
This project was created as a part of CS61A: Structure and Interpretation of Computer Programs using Python.

In this project, developed a simulator and multiple strategies for the dice game Hog. Used control statements and higher-order functions together to create this simulated dice game.

In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes.

Rules
To spice up the game, we will play with some special rules:

Pig Out. If any of the dice outcomes is a 1, the current player's score for the turn is 1.

Free Bacon. A player who chooses to roll zero dice scores one more than the minimum of of the ones and tens digit of the opponent's score

Swine Swap. After points for the turn are added to the current player's score, if the current and other player's scores share any digits in the same place value, the scores are swapped.
