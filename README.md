# TicTacToe Game (bash)

This is a Tic-tac-toe game written in Bash script (sh shell script) <br>
You can run it under any shell environment supporting bash (almost all Linux and Mac)

## Description

1. Just like any other Tic-tac-toe game, there are 9 blocks in total, stored in an array of 9 elements. <br>
Of course, this means that some calculations are needed to convert a 2D data to a 1D array. (row*3 + col) <br>
2. The whole game is in a big infinite loop, and there's no way to escape. (except closing the terminal or pressing Ctrl+c) <br>
This is because after the game finished, I hope we could simply type "restart", and then a new game would restart. <br>
Besides, every input is also wrapped up in a while loop, so that it continues only after getting the correct input. <br>

After all, in my opinion, the core of this game was the use of Array in bash, the assigning and dereferencing of it. <br>

## Screenshot

![Snapshot](screenshot.png)