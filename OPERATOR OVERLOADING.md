# Exp.No:27  
## Operator Overloading
---
### AIM  
To write a Python program to overload a comparison operator using a class named `A`.

---
### ALGORITHM
1. Begin the program.  
2. Define a class `A` with an `__init__` method that accepts a parameter `val` and assigns it to `self.val`.  
3. Define the `__gt__` method to overload the `>` operator:  
   - If `self.val` is greater than `other.val`, print `"ob1 is greater than ob2"`.  
   - Otherwise, print `"ob2 is greater than ob1"`.  
4. Create two objects `ob1 = A(2)` and `ob2 = A(3)`.  
5. Use the `>` operator to compare `ob1` and `ob2`.  
6. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
class A:
    def __init__(self, val):
        self.val = val

    def __gt__(self, other):
        if self.val > other.val:
            print("ob1 is greater than ob2")
        else:
            print("ob2 is greater than ob1")

ob1 = A(2)
ob2 = A(3)
ob1 > ob2
```

### OUTPUT
<img width="523" height="148" alt="image" src="https://github.com/user-attachments/assets/9e9f4780-8371-4ba6-83da-2038e899bfe5" />


### RESULT
Thus, the Python program to overload a comparison operator using class `A` has been successfully executed and the output is verified.
