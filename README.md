# Prime Checker
This program checks whether a given number is a prime number. A prime number is a natural number greater than 1 that has no positive divisors other than 1 and itself.

## Usage
Input the number to check: The user is prompted to enter a number.
Prime check: The program checks if the number is prime and prints the result.
Example
Input: 29

Output: "It's a prime number."

Input: 28

Output: "It's not a prime number."

## Concepts Used
Function Definition: The def keyword is used to define a function named prime_checker that takes one parameter number.

Boolean Flag: A boolean variable is_prime is used to keep track of whether the number is prime. It is initially set to True.

Loop Through Possible Divisors: A for loop iterates from 2 up to, but not including, the number itself to check for factors.

Modulo Operation: The % operator is used to determine if the number is divisible by any of the numbers in the loop. If it is divisible by any number, is_prime is set to False.

Conditional Statements: After the loop, an if statement checks the value of is_prime. If it is still True, the number is prime. Otherwise, it is not prime.

Input Function: The input() function is used to get user input for the number to be checked. The input is converted to an integer using the int() function.

Function Call: The prime_checker function is called with the user input as its argument.
