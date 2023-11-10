# Chess Game in C++

## Project Overview

This chess project is an exciting representation of the classic chess game. It's designed in C++ to provide a fun and educational way to learn the basics of programming.

## Project Contributors

The group members who contributed to this project are:

- Umair Imran (BS-DS-1B)
- Abdullah Arif (BS-DS-1B)

## Features

This chess program offers the following features:

- **Interactive Gameplay:** Players can make moves using the command line interface, enhancing their understanding of chess rules.
- **Chessboard Representation:** The chessboard is visually represented using ASCII characters, making it easy to follow the game.
- **Basic Chess Rules:** The project includes the fundamental rules of chess, such as piece movement, captures, and checkmate.

## How to Play

To play the chess game, follow these steps:

1. Clone or download the project from the GitHub repository.

2. Compile the C++ source code using a C++ compiler.

3. Run the executable to start the game.

4. Enter the source coordinates to pick a piece and the destination coordinates to place the piece e.g. 7a6a

## Console Sample Run

Here's a snippet of the chessboard:
![Alt Text](https://github.com/abdullaharif381/Programming-Fundamentals-CPP/blob/main/Chess/console_image_chess.png)

## Project Statement (Summary):
### Chess Logic/Rules/General functionalities of the program

- Set up a chess board with standard labeling of rows (1 to 8) and columns (a to h).
- Allow two players to make alternate moves.
- Check for invalid moves, including criteria like source square containing the current player's piece, valid move for the selected piece, and removal of check.
- Detect special conditions like check, checkmate, stalemate, castling, en passant, and pawn promotion.
- Offer classical, rapid, blitz, or lightning modes.
- Have additional capabilities for saving and loading games (max 3 games), player resignation, and player handshake.
- Use a simple sequential text file to store moves.
- Optionally, allow loading with replay (bonus).
- Time the game according to the chosen mode.
- Implement a text-based interface (minimum requirement) with standard coordinates for input.

### Interface (Graphics-Based - Bonus)
Optionally, you can implement a graphical interface using external graphics libraries. This is above and beyond the minimum requirement.
