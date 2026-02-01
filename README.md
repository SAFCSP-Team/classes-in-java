# Classes and Objects Project

### Objective

In this project, our main goal is to understand how to use classes and objects in Java.

### Problem
Create a `Book` class with `title` and `price` fields, three constructors, and a method to display information.

### Implementation

- Define a `Book` class with the following fields:
  -  String `title`.
  -  String `author`.
  -  Double `price`.
- Implement three constructors:
    - One that takes all three fields as parameters.
    - One that takes only `title` and `author` and sets `price` to 0.0.
    - A default constructor that sets `title` and `author` to `"Unknown"`, and `price` to 0.0.
- Add a `displayInfo()` method that prints the book's details.
- In the `main` method of the `Main` class:
    - Create three book objects using different constructors.
    - Use `displayInfo()` to print their details.
