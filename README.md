#rockPaperScissors

Objective: Create a JoKenPo game.

How?:
1 - The player chooses between three options: Rock, Paper or Scissors.
2 - The computer also chose an option, at the same time.
3 - The options are converted to numbers to reduce outcome options.

player rock = 2
player paper = 4
player scissors = 8

computer rock = -2
computer paper = -4
computer scissors = -8

Possible situations:

Even:           2+(-2) = 0
                4+(-4) = 0
                8+(-8) = 0

Player Win:     2 + (-8) = -6
                4 + (-2) = 2
                8 + (-4) = 4

Computer Win:   2 + (-4) = -2
                4 + (-8) = -4
                8 + (-2) = 6

3 - It's calculated the winner. 
4 - The game displays a message : "You won" or "You lose"