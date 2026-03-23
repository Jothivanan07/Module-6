# Exp.No:28  
## Abstraction
---
### AIM  
To write a Python program to define the abstract base class named `Polygon` and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the `sides()` method.

---
### ALGORITHM
1. Begin the program.  
2. Import the `ABC` class and `abstractmethod` from the `abc` module.  
3. Define the abstract base class `Polygon` that inherits from `ABC`.  
   - Define an abstract method `sides()` with no implementation.  
4. Define the `Triangle` class that inherits from `Polygon`.  
   - Implement the `sides()` method to print `"Triangle has 3 sides"`.  
5. Define the `Square` class that inherits from `Polygon`.  
   - Implement the `sides()` method to print `"I have 4 sides"`.  
6. Define the `Pentagon` class that inherits from `Polygon`.  
   - Implement the `sides()` method to print `"Pentagon has 5 sides"`.  
7. Define the `Hexagon` class that inherits from `Polygon`.  
   - Implement the `sides()` method to print `"Hexagon has 6 sides"`.  
8. Create objects of each subclass and invoke the `sides()` method.  
9. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
from abc import ABC, abstractmethod

class Polygon(ABC):
    @abstractmethod
    def sides(self):
        pass

class Triangle(Polygon):
    def sides(self):
        print("Triangle has 3 sides")

class Square(Polygon):
    def sides(self):
        print("I have 4 sides")

class Pentagon(Polygon):
    def sides(self):
        print("Pentagon has 5 sides")

class Hexagon(Polygon):
    def sides(self):
        print("Hexagon has 6 sides")

t = Triangle()
t.sides()
s = Square()
s.sides()
p = Pentagon()
p.sides()
k = Hexagon()
k.sides()
```

### OUTPUT
<img width="584" height="232" alt="image" src="https://github.com/user-attachments/assets/687d587d-6194-4b9d-b827-fc8f60387c40" />


### RESULT
Thus, the Python program to define the abstract base class `Polygon` and implement the abstract method in each subclass has been successfully executed and the output is verified.
