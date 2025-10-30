# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
I hard a hard time understanding classes at first, and it didn't elp when I made board a global variable. It worked until I got to the asserts, and had to change a lot of stuff around. Win conditions was tough, but your solution of making them all lists within lists was somethingI hadn't though of.

2. Explain how you would add a computer player to the game.
You could either make it place at random in unnocupied spaces, or maybe set up a function to have it detect when someone is abou to win and try to block them so it seems smarter.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
Make the computer check all winning combos, if the opponent has two out of three, and the tird space is unnocupied, have it place in that spot. You could also have it check to see if it has two out of three winning spots in a combo so it could go for the win itself.