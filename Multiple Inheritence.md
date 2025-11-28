# 5)e)Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

##  Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

##  Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## Program 
```
class value:
    def _init_(self,a,b):
        self.a=a
        self.b=b
class addition(value):
    def add(self):
        print(self.a+self.b)
class subtraction(value):
    def sub(self):
        print(self.a-self.b)
class division(value):
    def div(self):
        print(self.a/self.b)
        
a=int(input())
b=int(input())
add_1=addition(a,b)
add_1.add()
sub_1=subtraction(a,b)
sub_1.sub()
div_1=division(a,b)
div_1.div()
```

## Output Example
![operation](https://github.com/user-attachments/assets/927727c5-18f3-4e47-9dc2-000a891d48f8)

## Result
Thus a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance** is created





