# PIJ_assignments
repository for 2nd year Programming in Java course Assignments.
# Calculator Program

This Java program implements a simple calculator with basic arithmetic operations, as well as additional functionalities for calculating the mean and variance of a list of numbers.

## Classes

### Calculator

- `add(double a, double b)`: Adds two numbers `a` and `b`.
- `subtract(double a, double b)`: Subtracts `b` from `a`.
- `multiply(double a, double b)`: Multiplies two numbers `a` and `b`.
- `divide(double a, double b)`: Divides `a` by `b`. Handles division by zero case.
- `sqrt(double a)`: Computes the square root of a number `a`.
- `power(double a, double b)`: Raises `a` to the power of `b`.
- `mean(List<Double> numbers)`: Calculates the mean (average) of a list of numbers.
- `variance(List<Double> numbers)`: Calculates the variance of a list of numbers.

### Main2

This is the main class of the program that interacts with the user through the console.

#### Methods

- `main(String[] args)`: The entry point of the program. It displays a menu of operations, reads user input, and performs the selected operation.

## Input Methods

- `Scanner`: Used for reading input from the console.
- `BufferedReader`: Used for reading input from the console.
- `System.out.println()`: Used for printing output to the console.
