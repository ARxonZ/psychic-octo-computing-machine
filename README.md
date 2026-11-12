# Basic Calculator (Menu-Driven Program in C++)

## Description
This program allows the user to perform basic mathematical operations.
The user selects an operation from the menu, enters two numbers, and gets the result.
The menu repeats until the user chooses to exit.

## Operations
| Option | Operation      |
|--------|----------------|
| 1      | Addition       |
| 2      | Subtraction    |
| 3      | Multiplication |
| 4      | Division       |
| 5      | Exit           |

## Features
- Menu-driven interface that loops until the user exits
- Works with decimal numbers (`double`)
- Input validation: non-numeric input and invalid menu choices are handled
- Division by zero is detected and shows an error message
- Each operation is a separate function for clean, readable code

## How to Compile and Run
```bash
g++ calculator.cpp -o calculator
./calculator        # Windows: calculator.exe
```

## Sample Output
```
==============================
        BASIC CALCULATOR
==============================
  1. Addition
  2. Subtraction
  3. Multiplication
  4. Division
  5. Exit
------------------------------
Enter choice: 1
Enter first number: 10
Enter second number: 5
Result: 10.00 + 5.00 = 15.00

Enter choice: 4
Enter first number: 8
Enter second number: 0
Error: Division by zero is not allowed!

Enter choice: 5
Thank you for using the calculator. Goodbye!
```

## Concepts Used
Functions, `switch` statement, `do-while` loop, input validation with `cin`, `iomanip` formatting.

## Author
ARxon'Z
