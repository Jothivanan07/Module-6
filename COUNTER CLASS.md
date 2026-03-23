# Exp.No:30  
## COUNTER CLASS
---
### AIM  
To create an abstract class `Payment` with an abstract method `payment`. Create two subclasses `CreditCardPayment` and `MobileWalletPayment` which implement the abstract method. Invoke the method using the objects of the subclasses.

---
### ALGORITHM
1. Begin the program.  
2. Import the `ABC` class and `abstractmethod` from the `abc` module.  
3. Define the abstract class `Payment` that inherits from `ABC`.  
   - Define an abstract method `payment(self, amount)` with no implementation.  
4. Define the `CreditCardPayment` class that inherits from `Payment`.  
   - Implement the `payment(self, amount)` method to print the credit card payment details and return `True`.  
5. Define the `MobileWalletPayment` class that inherits from `Payment`.  
   - Implement the `payment(self, amount)` method to print the mobile wallet payment details and return `True`.  
6. Create objects of `CreditCardPayment` and `MobileWalletPayment`.  
7. Call the `payment()` method on each object and print the result.  
8. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
from abc import ABC, abstractmethod

class Payment(ABC):
    @abstractmethod
    def payment(self, amount):
        pass

class CreditCardPayment(Payment):
    def payment(self, amount):
        print("Credit card payment of- ", amount)
        print("Purchase of amount- ", amount)
        return True

class MobileWalletPayment(Payment):
    def payment(self, amount):
        print("Mobile wallet payment of- ", amount)
        print("Purchase of amount- ", amount)
        return True

obj1 = CreditCardPayment()
print(obj1.payment(100))

obj2 = MobileWalletPayment()
print(obj2.payment(200))
```

### OUTPUT
<img width="664" height="209" alt="image" src="https://github.com/user-attachments/assets/bb7c52d4-8b96-4b8a-814c-27667d153d3d" />


### RESULT
Thus, the Python program to create an abstract class `Payment` with subclasses `CreditCardPayment` and `MobileWalletPayment` has been successfully executed and the output is verified.
