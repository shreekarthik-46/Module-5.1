# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

##  Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

##  Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

##  Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
```
class details:
    def _init_(self):
        self.id=None
        self.name=""
        self.gender=""
    def get_input(self):
        self.id=int(input())
        self.name=input()
        self.gender=input()
    def display(self):
        print(f"Id:  {self.id}")
        print(f"Name:  {self.name}")
        print(f"Gender:  {self.gender}")
class employee(details):
    def _init_(self):
        details._init_(self)
         self.company=""
        self.dept=""
    def get_emp(self):
        self.get_input()
        self.company=input()
        self.dept=input()
    def display_emp(self):
        print("Employee Object")
        self.display()
        print(f"Company:  {self.company}")
        print(f"Department:  {self.dept}")
        print()
class patient(details):
    def _init_(self):
        details._init_(self)
        self.hospital=""
        self.dept=""
    def get_pat(self):
        self.get_input()
        self.hospital=input()
        self.dept=input()
    def display_pat(self):
        print("Patient Object")
        self.display()
        print(f"Hospital:  {self.hospital}")
          print(f"Department:  {self.dept}")
        
employee1=employee()
employee1.get_emp()
employee1.display_emp()

patient1=patient()
patient1.get_pat()
patient1.display_pat()
```

## Sample Output

![hirechy(1)](https://github.com/user-attachments/assets/7560d491-b1d1-4fdc-ab3a-9cf37d11ec8b)

## Result
Thus a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details is created.



