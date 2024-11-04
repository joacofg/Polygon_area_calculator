# Polygon_area_calculator
Overview
The Polygon Area Calculator project demonstrates the power of object-oriented programming in Python to create a versatile tool for calculating and visualizing the properties of rectangles and squares. This project features two primary classes: Rectangle and Square, with the Square class inheriting from the Rectangle class. The project showcases key OOP principles such as encapsulation, inheritance, and the use of special methods.

Features
Rectangle Class
The Rectangle class provides a comprehensive set of methods to work with rectangle shapes:

Initialization: The class is initialized with width and height attributes.

Setters: Methods to set the width (set_width) and height (set_height).

Getters:

get_area: Returns the area of the rectangle (width * height).

get_perimeter: Returns the perimeter of the rectangle (2 * width + 2 * height).

get_diagonal: Returns the length of the diagonal of the rectangle ((width ** 2 + height ** 2) ** 0.5).

Visualization:

get_picture: Returns a string representation of the rectangle using lines of '*' characters. If the width or height exceeds 50, it returns 'Too big for picture.'

Containment:

get_amount_inside: Takes another shape (square or rectangle) as an argument and returns the number of times the passed-in shape can fit inside the rectangle without rotation.

Square Class
The Square class inherits from the Rectangle class and is specifically designed for square shapes:

Initialization: The class is initialized with a single attribute side, which is used to set both the width and height of the square.

Setters:

set_side: Sets both the width and height of the square to the given side length.

The set_width and set_height methods are overridden to set both dimensions, ensuring the shape remains a square.

Special Methods
Both classes implement special methods to enhance their functionality and usability:

String Representation: The __str__ method provides a readable string representation of the object:

Rectangle: Outputs Rectangle(width=X, height=Y)

Square: Outputs Square(side=X)

This project serves as a practical example of how object-oriented programming can be used to solve geometric problems. It demonstrates the flexibility and power of Python classes and methods in creating reusable and extendable code.
