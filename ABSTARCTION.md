# Exp.No: 6A
## Abstraction

### AIM  
To write a Python program to define the abstract base class named `Polygon` and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the `sides()` method.


### ALGORITHM

1. **Start the Program.**
2. **Import the ABC class** from the `abc` module to implement abstraction.
3. **Define the abstract base class Polygon**:
   - Inherit from `ABC` (Abstract Base Class).
   - Define an abstract method `sides()` with no implementation.
4. **Define the Triangle class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Triangle has 3 sides"`.
5. **Define the Pentagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Pentagon has 5 sides"`.
6. **Define the Hexagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Hexagon has 6 sides"`.
7. **Define the Square class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"I have 4 sides"`.
8. **Create an object `t` of the Triangle class** and call the `sides()` method to print the number of sides.
9. **Create an object `s` of the Square class** and call the `sides()` method to print the number of sides.
10. **Create an object `p` of the Pentagon class** and call the `sides()` method to print the number of sides.
11. **Create an object `k` of the Hexagon class** and call the `sides()` method to print the number of sides.
12. **End the Program.**



### PROGRAM

from abc import ABC    <br />
class type_shape(ABC):  <br />
    #create abstract method area() <br />
    def area(self):    <br />
        pass   <br />

class Rectangle(type_shape): <br />
  length = 6  <br />
  breadth = 4      <br />
  def area(self):   <br />
    return self.length * self.breadth   <br />

class Circle(type_shape):  <br />
  radius = 7   <br />
  #define area function to calculate area  def area(self):     <br />
      return 3.14*self.radius*self.radius <br />

class Square(type_shape):   <br />
  length = 4 <br />
  #define area function to calculate area   <br />
  def area(self):    <br />
      return self.length*self.length  <br />

class triangle:  <br />
  length = 5 <br />
  width = 4 <br />
  #define area function to calculate area <br />
  def area(self): <br />
      return 0.5*self.length*self.width  <br />

r = Rectangle() # object created for the class 'Rectangle' <br />
c = Circle() # object created for the class 'Circle' <br />
s = Square() # object created for the class 'Square' <br />
t = triangle() # object created for the class 'triangle' <br />
print("Area of a rectangle:", r.area()) # call to 'area' method defined inside the class. <br />
print("Area of a circle:", c.area()) # call to 'area' method defined inside the class. <br />
print("Area of a square:", s.area()) # call to 'area' method defined inside the class. <br />
print("Area of a triangle:", t.area()) # call to 'area' method defined inside the class.

### OUTPUT

![Screenshot 2025-05-01 125606](https://github.com/user-attachments/assets/7c813955-1ec6-4d0d-b955-4cbe09436817)


### RESULT

Thus, the given python program is implemented and executed sucessfully.
