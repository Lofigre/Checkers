# Checkers // English Draughts

## Functionality:
Checkers (oficially "English Draughts") game with original rules. 

There are 2 game mods: with bot playing against you and 1v1

Game has a menu where you can choose the game mode and also where the winner of the last game is shown.

Unfortunately the recognition of a draw situation is yet to implement:( The game only ends when all pieces of one color are captured.

## Launching
Pygame module is required. The next command will satisfy this:

> pip install -r requirements.txt 

Then simply run *checkers.py*

> python3 checkers.py

## Some information
Wiki page with rules: https://en.wikipedia.org/wiki/English_draughts.

Some pecularities that may seem ridiculous:
- Black moves first
- Pieces can not capture backwards
- Kings can only move to adjacent diagonal squares. They also capture like standard pieces but can capture backwards

Here are some screenshots for you to understand how immature the project is...

![alt text](https://github.com/themeelanoid/Checkers/blob/main/screenshots/menu.png?raw=true)

![alt text](https://github.com/themeelanoid/Checkers/blob/main/screenshots/game.png?raw=true)

![alt text](https://github.com/themeelanoid/Checkers/blob/main/screenshots/end_of_a_game.png?raw=true)
