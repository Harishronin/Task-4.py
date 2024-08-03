
"""
Name:Harish kumar
Program1: create a python class called circle with constructor which will take a list as an argument[10,501,37,22,109,999,87,351]
date:02-Aug-2024
"""
class Circle:
    def __init__(self, radii):
        self.radii = radii

    def __repr__(self):
        return f"Circle(radii={self.radii})"

# Example usage
circle = Circle([10, 501, 37, 22, 109, 999, 87, 351])
print(circle)

"""
Name:Harish kumar
Program2: create a proper member variables inside the task and use them when necessary .for example for this task create a class private variable named pi=3.141
date:02-Aug-2024
"""
class Circle:
    __pi = 3.141  # Private class variable

    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return self.__pi * self.radius ** 2

    def circumference(self):
        return 2 * self.__pi * self.radius

# Example usage:
circle = Circle(5)
print("Area:", circle.area())
print("Circumference:", circle.circumference())


"""
Name:Harish kumar
Program3: create a proper member variables inside the task and use them when necessary .for example for this task create a class private variable named pi=3.141
date:02-Aug-2024
"""

class Shape:
    @classmethod
    def area(cls, dimensions):
        return [dimensions[i] * dimensions[i+1] for i in range(0, len(dimensions), 2)]

    @classmethod
    def perimeter(cls, dimensions):
        return [2 * (dimensions[i] + dimensions[i+1]) for i in range(0, len(dimensions), 2)]

# Example usage
dimensions = [10, 501, 37, 22, 109, 999, 87, 351]
print("Areas:", Shape.area(dimensions))
print("Perimeters:", Shape.perimeter(dimensions))

