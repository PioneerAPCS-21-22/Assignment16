# Assignment 16

For this assignment you will create a rock-paper-scissors game. You will use random
numbers to create a computer player and there will be a human player. You could also
try to make a more sophisticated AI, but that probably would require the use of an array or `ArrayList`.

Rules: Paper beats rock, but loses to scissors. Rock beats scissors, but loses to paper. Scissors beats paper, but loses to rock. [Play RPS online](https://www.afiniti.com/corporate/rock-paper-scissors).

**Note: you can find a pattern with determining the winner to save yourself from writing a lot of conditionals. Assign number values to the three options (e.g. 0 for rock, 1 for paper, and 2 for scissors). If the player picks a specific move, the move that beats it is to the right and the move that it beats is to the left.**

### Specifications

* You need to have 2 classes.

* Your `Runner`/`Main` class should only take input and call method(s) to run the game and/or print the result. All logic should be in your other class.

* Make sure to use `if`, `else if`, and `else` appropriately in your program.

### Sample Outputs

Ask the user to choose a move. After they make their move, say what the computer chose and then explain the result of the game.

```
Enter your move (1) rock, (2) paper, or (3) scissors: 2
The computer choose scissors.
Scissors beats paper.
You lose!
```

```
Enter your move (1) rock, (2) paper, or (3) scissors: 3
The computer chose paper.
Scissors beats paper.
You win!
```

```
Enter your move (1) rock, (2) paper, or (3) scissors: 1
The computer chose scissors.
Rock beats scissors.
You win!
```

```
Enter your move (1) rock, (2) paper, or (3) scissors: 3
The computer chose scissors.
You both chose scissors.
It's a draw!
```

```
Enter your move (1) rock, (2) paper, or (3) scissors: 0
Invalid move.
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

