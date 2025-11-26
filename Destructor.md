# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

##  Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

##  Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class Awesome:

    def greetings(self):
        print("Hello World!")

    def _del_(self):
        print("Hello from the _del_ method.")

obj = Awesome()  

obj.greetings()  

del obj
```

## Output
![del](https://github.com/user-attachments/assets/0f20c2d9-4588-4fdd-92fd-05b86f6d1f40)



## Result
Thus a project demonstrates how to implement a **destructor** in Python using a simple class is created.


