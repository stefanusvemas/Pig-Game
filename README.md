# Pig-Game
[Play Now](http://github.vemas.dev/Pig-Game/)

The **Pig Game** is a casual and entertaining dice game that combines luck and strategy. 
It can be played casually or competitively, and it's suitable for players of all ages.
## How to play

1. Both start with a score of 0.
1. On each turn, you'll roll the dice by clicking roll dice button
1. After each roll, you can see your score for that turn from the dice, then choose to roll again or hold.
    - If you choose to roll again, your turn continues, and your points for that turn keep accumulating.
    - If you roll again and get dice with value 1 (one), you lose all the points for that turn, and your turn ends.
    - If you choose to hold, your accumulated points for that turn will be added to your total score, and your turn ends.
1. The first player to reach or exceed 100 points wins the game.

## What I Learn
- DOM Manipulation

  DOM manipulation used to select HTML elements using 'querySelector' and 'getElementById' to manipulate their content, classes, and attributes.
- Implementing Game Logic

  The code includes functions to handle game logic such as initializing the game ('init'), switching players ('switchPlayer'), rolling the dice ('btnRoll' event listener), holding the score ('btnHold' event listener), and starting a new game ('btnNew' event listener).
- Variables and Data Structures

  The code uses variables like 'scores', 'currentScore', 'activePlayer', and 'playing' to keep track of total scores, current score, current active player, and the game state.
- CSS Manipulation

  The code modifies CSS classes ('classList') to show or hide elements ('hidden class') and switch styles ('player--active', 'player--winner').


  
  
You can see how these concepts come together to create the functionality of a Pig Game.

## Flow Chart
![flow chart](https://github.com/stefanusvemas/Pig-Game/blob/main/pig-game-flowchart.png)
