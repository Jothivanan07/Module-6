# Exp.No:29  
## Encapsulation
---
### AIM  
To create an `Employee` class by defining employee attributes such as `name` and `salary` as instance variables and implementing behavior using `work()` and `show()` instance methods.

---
### ALGORITHM
1. Begin the program.  
2. Define the `Employee` class.  
3. Inside the `Employee` class, define the `__init__` method to initialize `name` and `salary` as instance variables.  
4. Define the `show()` method to print the `name` and `salary` of the employee.  
5. Define the `work()` method to print the work details of the employee.  
6. Create an object of the `Employee` class with the name `'Jessa'` and salary `8000`.  
7. Call the `show()` method to display the employee details.  
8. Call the `work()` method to display the work details.  
9. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

    def show(self):
        print("Name: ", self.name, "Salary:", self.salary)

    def work(self):
        print(self.name, "is working on NLP")

emp = Employee("Jessa", 8000)
emp.show()
emp.work()
```

### OUTPUT
<img width="558" height="192" alt="image" src="https://github.com/user-attachments/assets/624500ea-2b4e-47aa-ba27-ecb4f1873ef8" />


### RESULT
Thus, the Python program to create an `Employee` class with instance variables and instance methods has been successfully executed and the output is verified.
