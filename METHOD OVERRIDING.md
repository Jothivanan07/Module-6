# Exp.No:26  
## Method Overriding
---
### AIM  
To write a Python program using the overloading operator for adding two objects.

---
### ALGORITHM
1. Begin the program.  
2. Define a class `A` with an `__init__` method that accepts a parameter `val` and assigns it to `self.val`.  
3. Define the `__add__` method to overload the `+` operator:  
   - Return a new object of class `A` with the sum of `self.val` and `other.val`.  
4. Define the `__str__` method to return the string representation of `self.val`.  
5. Accept two sets of inputs from the user (integers and strings).  
6. Create objects and use the `+` operator to add them.  
7. Print the results.  
8. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
class A:
    def __init__(self, val):
        self.val = val

    def __add__(self, other):
        return A(self.val + other.val)

    def __str__(self):
        return str(self.val)

a = int(input())
b = int(input())
c = input()
d = input()

obj1 = A(a)
obj2 = A(b)
obj3 = A(c)
obj4 = A(d)

print(": ", obj1 + obj2)
print(": ", obj3 + obj4)
```

### OUTPUT
<img width="430" height="225" alt="image" src="https://github.com/user-attachments/assets/3fa6e621-3e39-4eb9-a4bf-95a7f161f425" />


### RESULT
Thus, the Python program to overload the `+` operator for adding two objects has been successfully executed and the output is verified.
