# 2048_GAME
This is a simple implementation of the 2048 game written in C++. 2048 is a popular number puzzle game where the goal is to combine blocks with the same numbers on a 4x4 grid to achieve higher scores.

![image](https://github.com/xingyeahhh/2048_GAME/assets/123461462/859354e0-a607-413c-bf64-98c408344f11)

## Installation
To compile and run this game, you will need a C++ compiler such as g++. Follow these steps to install:


## Classes
### Grid
The Grid class represents the game board of the 2048 game, including the number blocks and the movement logic.

### Methods
Grid(): Create a new game board.

Grid(int initData[16]): Create a new game board with the given data.

void print() const: Print the current game board state.

int moveUp(): Move the blocks upwards and return the score.

int moveDown(): Move the blocks downwards and return the score.

int moveLeft(): Move the blocks to the left and return the score.

int moveRight(): Move the blocks to the right and return the score.

bool canMove() const: Check if there are still valid moves left.

bool canMoveUp() const: Check if it's possible to move up.

bool canMoveDown() const: Check if it's possible to move down.

bool canMoveLeft() const: Check if it's possible to move left.

bool canMoveRight() const: Check if it's possible to move right.

void spawn(size_t count = 1): Generate a specified number of new blocks on the game board.

void rotate(int numTurns): Rotate the game board.

## Game
The Game class represents the main control logic of the 2048 game.

### Methods
Game(): Create a new game instance.

void update(char*& message): Update the game state and return a message.

## game commands

- z : moves up
- q : moves left
- s : moves down
- d : moves right
- x : exits
