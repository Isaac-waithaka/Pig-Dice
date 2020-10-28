# _Pig Dice Game_

#### By ISAAC WAITHAKA

## Description

_This web application allows two players to play a game of Pig Dice._
The rules of the game are:
* When a player rolls a 1, their  total score reverts to 0 and it becomes the next player's turn.
* When the player rolls a 2 - 6, the score is added to their turn total and they can continue to play
* When the player chooses to "hold", their turn total is added to their total score, and it becomes the next player's turn.
* The player who first scores 100 or more points wins.

## Specifications
| Behavior        | Input           | Outcome  |
| ------------- |:-------------:| -----:|
| Player 1 clicks ROLL button | Click ROLL button | Dice rolls and number is generated
| If Player 1 rolls any number other than 1, that roll is added to round total | Roll = 2 | Round total = 2 |
| If Player 1 rolls a 1, no score is added and round for Player 1 ends | Roll = 1 | Round total = 2 / Total score = 2 / Player 2 begins |
| Repeat for Player 2 | Roll = 1 | Round total = 0 / Total score = 0 / Player 1 begins |
| When a player's total score reaches 100 or more, game ends and winner is shown | Player 1 total score = 100 | Winner page |


## Setup/Installation Requirements

* _Clone this repository_
* _Click [Pig Dice Game](https;//Isaac-waithaka.github.io/Pig-Dice)To Play_


## Technologies Used

* _HTML_
* _CSS_
* _Bootstrap_
* _JavaScript_
* _jQuery_

### License

*This software is licensed under the MIT license.*

Copyright (c) 2020 **_Waithaka Isaac_**
