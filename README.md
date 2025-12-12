# Command-Line Calculator

A simple, interactive command-line calculator written in Python that supports basic arithmetic operations and keeps track of your calculation history.

## Features

- **Basic Arithmetic Operations**
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
  - Power/Exponentiation (^)
  - Remainder/Modulo (%)

- **Additional Features**
  - Calculation history tracking
  - View past calculations
  - Reset functionality
  - Input validation
  - Error handling for invalid operations

## Installation

1. Clone this repository:
```bash
git clone https://github.com/pasindulekamwasam/simple-python-calculator.git
cd simple-python-calculator
```

2. Ensure you have Python 3.x installed:
```bash
python --version
```

## Usage

Run the calculator:
```bash
python cal ver.02.py
```

### Menu Options

When you run the program, you'll see the following menu:
```
Select operation.
1.Add      : + 
2.Subtract : - 
3.Multiply : * 
4.Divide   : / 
5.Power    : ^ 
6.Remainder: % 
7.Terminate: # 
8.Reset    : $ 
9.History  : ? 
```

### Examples

**Addition:**
```
Enter choice(+,-,*,/,^,%,#,$,?): +
Enter first number: 5
Enter second number: 3
5.0 + 3.0 = 8.0
```

**View History:**
```
Enter choice(+,-,*,/,^,%,#,$,?): ?
5.0 + 3.0 = 8.0
10.0 - 2.0 = 8.0
```

**Terminate:**
```
Enter choice(+,-,*,/,^,%,#,$,?): #
Done. Terminating
```

### Special Commands

- **#** - Terminate the program
- **$** - Reset and return to main menu
- **?** - Display calculation history
- You can also append **#** or **$** to any number input to trigger these commands

## Requirements

- Python 3.x
- No external dependencies required

## Error Handling

The calculator includes error handling for:
- Invalid number inputs (prompts for re-entry)
- Division by zero (returns None and displays error)
- Invalid operations (displays error message)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Pasindu Madhusara Lekamwasam

Project Link: [https://github.com/pasindulekamwasam/simple-python-calculator](https://github.com/pasindulekamwasam/simple-python-calculator)

## Acknowledgments

- Thanks to everyone who has contributed to this project
- Inspired by the need for a simple command-line calculator
