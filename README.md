# Homework: Functions and Lambda Functions

## Basic Exercises

### Functions

1. **Basic Function**

   - Write a function `greet` that takes a name as an argument and prints "Hello, [name]!".

2. **Sum Function**

   - Write a function `sum_numbers` that takes two numbers as arguments and returns their sum.

3. **Square Function**

   - Write a function `square` that takes a number as an argument and returns its square.

4. **List of Squares**

   - Write a function `list_of_squares` that takes a list of numbers and returns a new list with the squares of those numbers.

5. **Factorial Function**

   - Write a function `factorial` that takes a number as an argument and returns its factorial.

6. **Palindrome Checker**
   - Write a function `is_palindrome` that takes a string and returns `True` if the string is a palindrome and `False` otherwise.

### Lambda Functions

1. **Square Lambda**

   - Write a lambda function that takes a number and returns its square. Assign it to a variable named `square_lambda`.

2. **Sum Lambda**

   - Write a lambda function that takes two numbers and returns their sum. Assign it to a variable named `sum_lambda`.

3. **Even Numbers Filter**

   - Use a lambda function with the `filter` function to filter out even numbers from a list of numbers.
     ```python
     numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
     ```

4. **Length of Strings**

   - Use a lambda function with the `map` function to convert a list of strings into a list of their lengths.
     ```python
     words = ["apple", "banana", "cherry"]
     ```

5. **Sort Tuples**

   - Use a lambda function with the `sorted` function to sort a list of tuples based on the second element of each tuple.
     ```python
     tuples = [(1, 'one'), (2, 'two'), (3, 'three')]
     ```

6. **Conditional Lambda**
   - Write a lambda function that takes a number and returns "Even" if the number is even and "Odd" if the number is odd. Assign it to a variable named `even_odd_lambda`.

## Optional

1. **Fibonacci Function**

   - Write a function `fibonacci` that takes a number `n` and returns a list of the first `n` Fibonacci numbers.

2. **Prime Checker**

   - Write a function `is_prime` that takes a number and returns `True` if the number is prime and `False` otherwise.

3. **List of Primes**

   - Write a function `list_of_primes` that takes a number `n` and returns a list of all prime numbers up to `n`.

4. **Lambda with Multiple Conditions**

   - Write a lambda function that takes a number and returns "Fizz" if it is divisible by 3, "Buzz" if it is divisible by 5, and "FizzBuzz" if it is divisible by both. Assign it to a variable named `fizzbuzz_lambda`.

5. **Lambda and Reduce**
   - Use a lambda function with the `reduce` function from the `functools` module to find the product of a list of numbers.
     ```python
     numbers = [1, 2, 3, 4, 5]
     ```
