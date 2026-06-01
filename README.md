# Boggle Word Search using Trie

A highly efficient implementation of the classic word game Boggle, developed as a Data Structures and Algorithms (DSA) project. This project utilizes a Trie (Prefix Tree) data structure to drastically optimize the word search process on the Boggle board.

## Project Files
* **game.py**: The core application file containing the Trie data structure implementation, the Boggle board generation, and the main game logic.

## Why a Trie?
In a standard Boggle game, searching for valid words using brute-force (checking every possible path against a dictionary) is computationally expensive. By implementing a Trie, the algorithm can instantly abandon invalid character paths (prefixes that don't exist in the dictionary), turning a time-consuming search into a highly optimized process. 

## Tech Stack
* **Language**: Python
* **Concepts**: Data Structures, Tries (Prefix Trees), Depth-First Search (DFS), Algorithm Optimization

## Setup Instructions
1. Ensure Python is installed on your machine.
2. Run `game.py` to launch the Boggle game and word search algorithm.
