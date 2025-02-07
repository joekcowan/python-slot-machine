# Slot Machine Program

## Description
This is a simple command-line slot machine game written in Python. The program allows users to deposit money, place bets, and spin the slot machine. If the user wins, their balance is updated accordingly. The game continues until the user chooses to quit.

## Features
- Allows users to deposit money before playing.
- Users can select the number of lines they want to bet on.
- Bets are placed on each line, with adjustable amounts.
- A random slot machine spin is generated.
- The program checks for winnings and updates the balance.
- The game continues until the user decides to quit.

## How to Play
1. Run the program using Python.
2. Enter an amount to deposit.
3. Choose the number of lines to bet on (1-3).
4. Place a bet amount within the allowed range.
5. The slot machine will spin and display the result.
6. Any winnings will be added to your balance.
7. Repeat the process until you decide to quit by entering 'q'.
8. Your final balance will be displayed before the program exits.

## Rules
- The slot machine consists of a 3x3 grid (3 rows, 3 columns).
- Symbols have different frequencies and values:
  - 'A' appears 2 times, worth 5x the bet amount.
  - 'B' appears 4 times, worth 4x the bet amount.
  - 'C' appears 6 times, worth 3x the bet amount.
  - 'D' appears 8 times, worth 2x the bet amount.
- Winning occurs when the same symbol appears in a full line.
- Winnings are calculated based on the symbol values and the bet amount.

## Requirements
- Python 3.x

## Running the Program
To run the program, execute the following command in a terminal or command prompt:
```sh
python slot_machine.py
```

## Example Gameplay
```
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to $20.
A | B | C
D | A | B
C | D | A
You won $50.
You won on line: 1
Current balance is $130
Press enter to play (q to quit).
```

This program was created as a simple demonstration of Python programming logic and randomness.

