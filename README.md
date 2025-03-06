# Calculator

A simple Python-based calculator that lets you perform basic arithmetic operations (add, subtract, multiply, and divide) with a continuous calculation feature.

## Concepts Implemented

- Functions with return values
- Recursion
- Looping 
- Conditional Statements
- Dictionaries
- Datatypes conversion

## Features

- Basic arithmetic operations:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
- Continuous calculation with previous results
- ASCII art calculator interface
- Interactive command-line interface

## Files

- [`main.py`](main.py): Contains the calculator logic and user interface
- [`art.py`](art.py): Contains the ASCII art logo for the calculator
- `README.md`: This documentation file
- `LICENSE`: MIT license file

## How to Use

1. Run the `main.py` script
2. Enter the first number
3. Choose an operator (+, -, *, /)
4. Enter the second number
5. View the result
6. Choose to either:
   - Continue calculating with the result
   - Start a new calculation

## Example

```sh
 _____________________
|  _________________  |
| | Pythonista   0. | |  .----------------.  .----------------.  .----------------.  .----------------. 
| |_________________| | | .--------------. || .--------------. || .--------------. || .--------------. |
|  ___ ___ ___   ___  | | |     ______   | || |      __      | || |   _____      | || |     ______   | |
| | 7 | 8 | 9 | | + | | | |   .' ___  |  | || |     /  \     | || |  |_   _|     | || |   .' ___  |  | |
| |___|___|___| |___| | | |  / .'   \_|  | || |    / /\ \    | || |    | |       | || |  / .'   \_|  | |
| | 4 | 5 | 6 | | - | | | |  | |         | || |   / ____ \   | || |    | |   _   | || |  | |         | |
| |___|___|___| |___| | | |  \ `.___.'\  | || | _/ /    \ \_ | || |   _| |__/ |  | || |  \ `.___.'\  | |
| | 1 | 2 | 3 | | x | | | |   `._____.'  | || ||____|  |____|| || |  |________|  | || |   `._____.'  | |
| |___|___|___| |___| | | |              | || |              | || |              | || |              | |
| | . | 0 | = | | / | | | '--------------' || '--------------' || '--------------' || '--------------' |
| |___|___|___| |___| |  '----------------'  '----------------'  '----------------'  '----------------' 
|_____________________|

Type the first number: 5
+
-
*
/
Type the operator: +
Type the second number: 3
5 + 3 = 8
Do you want to proceed with 8? Type 'y' if yes, type 'n' to start over.
```

## Implementation Details

The calculator uses:
- Dictionary of operator symbols mapped to functions
- Recursive function for continuous calculations
- Float numbers for decimal support
- While loop for operation continuity
