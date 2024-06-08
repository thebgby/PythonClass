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

6. **Class with Properties**
   - Create a class named `Temperature` with a single attribute `celsius` (float).
     Add a property `fahrenheit` to get the temperature in Fahrenheit using the formula `(celsius * 9/5) + 32`.
     Add a setter for the `fahrenheit` property to set the temperature in Celsius.

## Optional

1. **Class with Static Method**

   - Create a class named `MathUtils` with a static method `add` that takes two numbers and returns their sum.

2. **Class Method**

   - Create a class named `Employee` with the following attributes:
     - `name` (string)
     - `salary` (float)
       Add a class method `from_string` that takes a string in the format "name,salary" and returns an instance of `Employee`.

3. **Magic Methods**

   - Create a class named `Vector` with the following attributes:
     - `x` (float)
     - `y` (float)
       Implement the magic method `__add__` to add two vectors and return a new `Vector` object.

4. **Context Manager Class**

   - Create a class named `FileHandler` that implements the context manager methods (`__enter__` and `__exit__`) to handle opening and closing a file. Use this class to read the contents of a file.

5. **Metaclass**

   - Create a metaclass named `UppercaseMeta` that converts all class attribute names to uppercase.

6. **Dataclass**
   - Create a class named `Point` using the `dataclasses` module with the attributes:
     - `x` (float)
     - `y` (float)
