# Aces High Card Game

## Introduction
This project implements a console-based card game where the player manages a deck and tries to move all non-ace cards to a foundation according to specific rules.

## Game Description
"Aces High Card Game" involves a tableau of four columns and a stock of cards. The player moves cards within the tableau and to the foundation to achieve the game's goal - to have only the four aces remaining in the tableau.

## Rules
- Tableau columns are numbered 1 to 4.
- Only the card at the bottom of a Tableau column can be moved.
- A card can be moved to the Foundation only if a higher-ranked card of the same suit is at the bottom of another Tableau column.
- The game is won when all cards except the aces are moved to the Foundation.

## Features
- **Initialize Game**: Sets up the game with a shuffled deck and distributes one card to each tableau column.
- **Deal to Tableau**: Deals one card to each column from the stock.
- **Move to Foundation**: Moves a card from a tableau column to the foundation if valid.
- **Move within Tableau**: Moves a card between tableau columns.
- **Check for Win**: Checks if the game has been won.
- **Display**: Shows the current state of the stock, tableau, and foundation.

## Menu Options
- `D`: Deal to the Tableau (one card on each column).
- `F x`: Move card from Tableau column x to the Foundation.
- `T x y`: Move card from Tableau column x to empty Tableau column y.
- `R`: Restart the game (after shuffling).
- `H`: Display the menu of choices.
- `Q`: Quit the game.

## Setup and Installation
Clone the repository and run the program in a Python environment that supports Python 3.x. Ensure that the `cards` module is correctly imported and available in your Python environment.

## How to Play
1. Start the game to initialize the tableau and stock.
2. Use the menu options to manipulate the game state:
   - Deal cards, move cards to the foundation, or between tableau columns.
   - Check the rules and current game status by invoking the display function.
3. Aim to move all non-ace cards to the foundation as per the game's rules.
4. Restart or quit the game as needed using the menu options.

## Contributions
- This game is designed as a part of a computer science project. Contributions and improvements are welcome via pull requests.

Enjoy the game and test your logical thinking and planning skills!
