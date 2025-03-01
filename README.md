# Odd or Even Checker (for numbers 1 to 1 million)

This Python script is a playful and inefficient way to check whether a given number (from 1 to 1 million) is odd or even. While it's not optimized for large numbers, it highlights the inefficiencies of using a series of conditional statements (`if` statements) to perform a simple task.

## Script Overview

The script asks for a user input number and checks it against a set of conditions. If the number matches one of the pre-defined numbers (1 through 17), it prints whether the number is odd or even.

However, for large numbers (e.g., up to 1 million), this method becomes highly inefficient, as it requires checking each number individually using multiple `if` conditions.

## Why This is a Joke

While the task of checking if a number is odd or even is trivial and can be done efficiently using the modulo operator (`%`), this script uses multiple `if` statements, one for each number. The script checks for conditions up to 1 million (as a joke).

## Example Code

```python
number = int(input("Enter a number: "))

if number == 1: print("Number is Odd")
if number == 2: print("Number is Even")

