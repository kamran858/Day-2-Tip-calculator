# Tip Calculator

A Python program that calculates how much each person should pay when splitting a restaurant bill with tip.

## Description

This interactive tip calculator helps groups of people split restaurant bills fairly. The program takes the total bill amount, desired tip percentage, and number of people, then calculates exactly how much each person should pay including their share of the tip.

## How to Run

1. Make sure you have Python installed on your computer
1. Download the `task.py` file
1. Open terminal/command prompt
1. Navigate to the project folder
1. Run the command:
   
   ```
   python task.py
   ```

## How it Works

1. Welcomes you to the tip calculator
1. Asks for the total bill amount
1. Asks what percentage tip you’d like to give (10%, 12%, or 15%)
1. Asks how many people are splitting the bill
1. Calculates each person’s share including tip
1. Displays the final amount each person should pay (rounded to 2 decimal places)

## Example Usage

```
Welcome to the tip calculator!
What was the total bill? $124.56
What percentage tip would you like to give? 10, 12, or 15? 12
How many people to split the bill? 7

Each person should pay: $19.93
```

## Calculation Process

1. **Calculate tip amount**: `bill × (tip_percentage ÷ 100)`
1. **Calculate total with tip**: `bill + tip_amount`
1. **Split among people**: `total_with_tip ÷ number_of_people`
1. **Round to 2 decimal places**: Using `round()` function

## What I Learned

- Taking user input with `input()` and converting to appropriate data types
- Using `float()` for decimal numbers and `int()` for whole numbers
- Mathematical operations and calculations
- Using the `round()` function to format money properly
- String formatting and concatenation
- Creating interactive console applications
- Input validation and user-friendly prompts

## Technologies Used

- Python 3
- Built-in functions: `input()`, `float()`, `int()`, `round()`, `print()`

## Project Context

This is Day 2 of my 100 Days of Code Python learning journey. It focuses on data types, mathematical operations, and creating practical utility programs.

-----

*Created as part of 100 Days of Code - Python Bootcamp*
