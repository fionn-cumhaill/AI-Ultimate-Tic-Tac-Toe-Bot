# AI-Ultimate-Tic-Tac-Toe-Bot
An AI Bot capable of playing 16x16 variant of Ultimate Tic-Tac-Toe

The search algorithm used in this bot is MTD(f) algorithm, as developed by Aske Plaat.
More information and the pseudocode can be found here - https://people.csail.mit.edu/plaat/mtdf.html

Zobrist Hashing is used to identify board states that have occurred before.
Move Reordering has been used to get faster cutoffs.

This is a work in progress, with plans to add many more features in the future.
The code might have bugs, and any help whatsoever in identifying and fixing them is most welcome :)
