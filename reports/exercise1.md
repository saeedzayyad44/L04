# Bug reports for exercise1.py

Line: 3
Problem: the docstring says "true for even numbers", but the function returns True when n % 2 == 1, which is for odd numbers.
Example: is_even(4) returns False, expected True.
Fix: return n % 2 == 0

Line: 8
Problem: the docstring says "area of a rectangle", but the function returns width + height, which is the perimeter, not the area.
Example: rectangle_area(3, 4) returns 7, expected 12.
Fix: return width * height

Line: 12
Problem: the docstring says "twice the number n", but the function returns n + 2, which is not twice the number.
Example: double(5) returns 7, expected 10.
Fix: return n * 2
