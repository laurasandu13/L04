# Bug reports for exercise1.py

Line: 3
Problem: is_even returns True for odd numbers (like 1, 3, 5) but the docstring says it should be true for even numbers.
Example: is_even(2) returns False, expected True.
Fix: return n % 2 == 0

Line: 8
Problem: rectangle_area returns the sum of width and height, but the docstring says it should return the area (width times height).
Example: rectangle_area(4, 5) returns 9, expected 20.
Fix: return width * height

Line: 12
Problem: double returns n + 2, but the docstring says it should return twice the number (n * 2).
Example: double(3) returns 5, expected 6.
Fix: return n * 2
