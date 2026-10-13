# Python Calculator

## 1. Introduction

This project is a simple Python calculator that performs the four basic mathematical operations: addition, subtraction, multiplication, and division. It uses functions to calculate the answers and user input to select the desired operation.

## 2. Explanation of the Code

### A. Mathematical Functions

```python
def add_numbers(num1, num2):
    return num1 + num2

def subtract_numbers(num1, num2):
    return num1 - num2

def multiply_numbers(num1, num2):
    return num1 * num2

def divide_numbers(num1, num2):
    return num1 / num2
```

**Explanation:**

- `def add_numbers(num1, num2):` defines a function that adds two numbers.
- `return num1 + num2` returns the sum of the two numbers.
- `def subtract_numbers(num1, num2):` defines a function that subtracts the second number from the first.
- `return num1 - num2` returns the difference between the numbers.
- `def multiply_numbers(num1, num2):` defines a function that multiplies two numbers.
- `return num1 * num2` returns the product of the numbers.
- `def divide_numbers(num1, num2):` defines a function that divides the first number by the second.
- `return num1 / num2` returns the quotient of the numbers.

### B. Getting User Input

The program asks the user to enter two numbers and converts their inputs into floating-point numbers so that decimal values can be used.

### C. Displaying the Operations

The program displays a menu containing addition, subtraction, multiplication, and division. This allows the user to choose which mathematical operation to perform.

### D. Choosing an Operation

The program uses conditional statements such as `if`, `elif`, and `else` to determine which operation the user selected. It then calls the corresponding function to calculate the answer.

### E. Displaying the Result

After performing the selected operation, the program displays the calculated result using the `print()` function.

### F. Handling Division by Zero

Before dividing, the program checks whether the second number is zero. Since division by zero is undefined, the program displays an error message instead of performing the calculation.

### G. Handling Invalid Choices

If the user enters a choice that is not among the available operations, the program displays an invalid-choice message.

## 3. Conclusion

This project demonstrates the use of Python functions, variables, user input, arithmetic operators, conditional statements, and basic error handling. It shows how these programming concepts can work together to create a simple calculator.

