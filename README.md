# Monty Hall Empirical Approach

The Monty Hall problem is a brain teaser, in the form of a probability puzzle, loosely based on the American television game show Let's Make a Deal and named after its original host, Monty Hall.

This is a script to run N trials to see the results of the monty hall problem. If you want to play the Monty Hall Problem and have a feel for the problem, you can run the `play.py` file.

## What is The Monty Hall Problem

(Taken from [BetterExplained](https://betterexplained.com/articles/understanding-the-monty-hall-problem/))  

The Monty Hall problem is a counter-intuitive statistics puzzle:

- There are 3 doors, behind which are two goats and a car.
- You pick a door (call it door A). You’re hoping for the car of course.
- Monty Hall, the game show host, examines the other doors (B & C) and opens one with a goat. (If both doors have goats, he picks randomly.)

Here’s the problem: Do you stick with door A (original guess) or switch to the unopened door? Does it matter?

Surprisingly, the odds aren’t 50-50. If you switch doors you’ll win 2/3 of the time!

To understand the classical and proper solution without bruteforcing, visit [Understanding The Monty Hall Problem](https://betterexplained.com/articles/understanding-the-monty-hall-problem/)

## Solving Using an Empirical Approach

In this script, we would try to solve the problem by brute force, getting the results of the trials and tallying them up.

## How to Use

This uses vanilla Python, so we don't need to install other libraries. Just run `main.py` to see the results with the default configuration. To change the variables of the game, the following variables can be changed:

- N_DOORS - Total number of doors. (default is 3)
- N_TO_OPEN - Number of doors to open at the start. (default is 1)
- N_TESTS - Number of trials to run. (Default is 10000)
- SWITCH_CHOICE - On each trial, should the player switch or stay? (default is to switch)
  - `w` is for switch
  - `s` to stay

## Author

Christian Klint M. Labadia (when I was bored on a random day at 2am)
