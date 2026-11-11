# Number Guessing Game

A simple console-based number guessing game written in C.

## About
The computer picks a random number between 1 and 100. The player keeps guessing, and the program says whether each guess is too high or too low until the correct number is found. At the end it shows how many attempts were taken.

## Concepts used
- Random number generation (`rand()` and `srand()`)
- `do-while` loop
- `if / else if / else` statements
- Input and output with `scanf()` and `printf()`

## How to compile and run

Compile:

    gcc guess_game.c -o guess_game

Run:

    ./guess_game

On Windows, run `guess_game.exe` instead of `./guess_game`.

## Author
Shabber Murtaza
