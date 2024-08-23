
#  Slot Machine  

This Slot Machine project is a simple command-line game implemented in Python. The user can deposit money, place bets on different lines, and spin the slot machine to see if they win based on the symbols that appear. The game calculates the winnings based on the symbols' values and the bet placed by the user.


## Features

Deposit Money: The user can deposit money to play the slot machine.

Place Bets: The user can place a bet on up to 3 lines with a bet amount within a specified range.

Spin the Slot Machine: The slot machine will randomly generate symbols across 3 columns and 3 rows.

Check Winnings: The game will check if the user has won based on the symbols aligned on the lines they bet on and will calculate the winnings accordingly.

Display Results: The game displays the current balance, the results of each spin, and the lines on which the user won.



## How to play


Run the Program: Start the game by running the main() function in the script.

Deposit Money: The game will prompt you to deposit money. Enter the amount you wish to deposit. The amount must be a positive integer. 

Select Number of Lines: Choose the number of lines you want to bet on. The maximum number of lines is 3.

Place a Bet: Enter the amount you want to bet on each line. The bet must be between the minimum and maximum bet values. The game will calculate the total bet as the bet per line multiplied by the number of lines.

Spin the Slot Machine: The slot machine will spin and display a 3x3 grid of symbols. The game will check if you have won based on the symbols on the lines you bet on.

Check Your Winnings: The game will display the amount you won and the lines on which you won. Your balance will be updated accordingly.

Continue Playing or Quit: You can choose to spin again or quit the game. If you decide to quit, the game will display your final balance.


## Symbolic values

The slot machine uses the following symbols, each with a different value and occurrence probability:

A: Appears 2 times, worth $5 per symbol.

B: Appears 4 times, worth $4 per symbol.

C: Appears 6 times, worth $3 per symbol.

D: Appears 8 times, worth $2 per symbol.


## Requirements


Python 3.6+: The game uses f-strings, which are only available in Python 3.6 and above.

Random Module: The script uses Python’s built-in random module for generating the slot machine spins.

