# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

The has_won was the function I had most difficulty with because I had to go through each way to win and with the offset of counting starting at 0 I had trouble with that.

2. Explain how you would add a computer player to the game.

the first thing I would do is change the loops to allow for turns to switch off between users as well as implement a difficulty setting making the computer have a better route to victory the harder the difficulty

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

I would get it to go through the board recursively looking through every possible move and way to win and also allow for a bactrack function to help in choose the best move from a list of the best moves.