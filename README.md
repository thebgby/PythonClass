# Homework: Classes in Python

## Basic Exercises

1. **Create a Simple Class**

   - Create a class named `Person` with the following attributes:
     - `name` (string)
     - `age` (integer)
       Add a method `introduce` that prints "Hello, my name is [name] and I am [age] years old."

2. **Constructor Method**

   - Modify the `Person` class to include a constructor (`__init__` method) that initializes the `name` and `age` attributes.

3. **Class with Multiple Methods**

   - Create a class named `Rectangle` with the following attributes:
     - `length` (float)
     - `width` (float)
       Add methods to:
     - Calculate and return the area of the rectangle.
     - Calculate and return the perimeter of the rectangle.

4. **Class Inheritance**

   - Create a base class named `Animal` with a method `make_sound` that prints "Some generic sound".
   - Create a subclass named `Dog` that inherits from `Animal` and overrides the `make_sound` method to print "Bark".

5. **Private Attributes and Methods**

   - Create a class named `BankAccount` with the following private attributes:
     - `__balance` (float)
       Add methods to:
     - Deposit an amount to the account.
     - Withdraw an amount from the account.
     - Check the account balance.
