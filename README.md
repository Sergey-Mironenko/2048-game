# 2048 game

  2048 is a single-player sliding block puzzle game. The game’s objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

# [DEMO](https://Sergey-Mironenko.github.io/2048-game/)

# Technologies used

  - HTML
  - CSS
  - Sass (SCSS)
  - JavaScript

# Game logic

  - The game field is 4 x 4 (16 cells)
  - Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
  - The game starts with 2 cells filled with 2 or 4
  - The game can be started by clicking the Start button
  - The player can move cells with keyboard arrows
  - All the numbers are moved in the selected direction until all empty cells are filled in
  - 2 equal cells are merged into a doubled number
  - The merged cell can’t be merged twice during one move
  - The move is possible if at least one cell is changed after the move
  - After move 2 or 4 appears in a random empty cell. 4 probability is 10%
  - When 2048 value is displayed in any cell, win message will be shown.
  - The game over message will be shown if there are no more available moves.
  - Score is increased by the sum of all merged cells.
  - The game can be restarted by clicking the Restart button after more then one move.

# How to run the project locally

  - Fork and clone this repository
  - Run npm install in your terminal
  - Run npm start to start the project locally

# Dependencies

  - Node v14.21.3 or higher
  - npm v6.4.18 or higher

# Reflections

The main goal of this project was to practice JavaScript and DOM manipulations and combine JavaScript with HTML and CSS.

The main challenge was to implement the game logic. I had to think about all possible scenarios and how to implement them.

Eventually I practiced in building more complex logic using knowledge I have gained so far until this point.

### This project is inspired by original [2048 game](https://play2048.co/)