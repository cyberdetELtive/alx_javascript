JavaScript - Objects, Scopes, Closures
This repository contains JavaScript programs that demonstrate the concepts of objects, scopes, and closures. Each program focuses on different aspects of these concepts.

Task 0: 0-rectangle.js
In this task, we define an empty class Rectangle that represents a rectangle. The goal is to practice creating a class using the class notation in JavaScript.

Task 1: 1-rectangle.js
In this task, we define a class Rectangle that represents a rectangle. This class takes two arguments, width and height, and initializes instance attributes with these values.

Task 2: 2-rectangle.js
In this task, we improve the Rectangle class by adding a condition to handle cases where width or height is equal to 0 or not a positive integer. In such cases, we create an empty object.

Task 3: 3-rectangle.js
In this task, we enhance the Rectangle class further by adding an instance method called print(). This method prints a rectangle using the character 'X'. The number of 'X' characters printed horizontally is determined by the width, and the number of rows is determined by the height.

Task 4: 4-rectangle.js
In this task, we continue working with the Rectangle class. We add two new instance methods:

rotate(): This method exchanges the width and height of the rectangle.
double(): This method multiplies the width and height of the rectangle by 2.

Task 5: 5-square.js
In this task, we create a new class Square that inherits from the Rectangle class. The Square class represents a square and takes a single argument, size, in its constructor. It calls the constructor of the parent class Rectangle using super(size, size).

Task 6: 6-square.js
In this task, we extend the Square class by adding an instance method called charPrint(c). This method prints the square using the character c, and if c is undefined, it uses the character 'X' by default.