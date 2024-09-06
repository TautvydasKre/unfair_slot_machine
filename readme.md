# Slot Machine Game

A simple slot machine game written in Python where players can deposit money, place bets on multiple lines, and spin the slot machine for a chance to win based on matching symbols.

## Table of Contents
- [Game Rules](#game-rules)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Features](#features)

## Game Rules

1. The player deposits an initial amount to start the game.
2. The player bets on up to 3 lines and can wager between $1 and $100 per line.
3. The slot machine consists of 3 rows and 3 columns. Symbols "A", "B", "C", and "D" have different probabilities and payouts:
   - **A**: Appears 2 times, pays 5x the bet per line.
   - **B**: Appears 4 times, pays 4x the bet per line.
   - **C**: Appears 6 times, pays 3x the bet per line.
   - **D**: Appears 8 times, pays 2x the bet per line.
4. Winnings are calculated if the symbols on a line match across all three columns. 
5. The game continues until the player decides to quit or runs out of money.

## Installation

1. Ensure you have Python installed on your system (version 3.x).
2. Clone this repository or download the Python script.

```bash
git clone https://github.com/your-repo/slot-machine.git
```
Navigate to the project directory
```bash
cd slot-machine
```
4. Run the game:
```bash
python slot_machine.py
```
## How to Play

1. Deposit money: You start by entering the amount of money you wish to deposit into the game.
2. Select number of lines: Choose how many lines (1-3) you want to bet on.
3. Place your bet: Enter how much you want to bet on each line (between $1 and $100).
4. Spin: The slot machine will spin and display the symbols. You win if the symbols on a line match across all three columns.
5. Winnings: Your total balance will be updated with any winnings or losses, and you can continue playing or quit.

## Features

- Flexible Betting: Bet on up to 3 lines with customizable amounts.
- Randomized Slot Machine: Each spin is randomized with varying probabilities for symbols.
- Real-time Winnings Calculation: Instant feedback on your winnings and remaining balance.
- Simple Interface: Text-based interface for easy interaction.