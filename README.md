# User-defined-Modules-and-Classes-in-Python

## 1. Classes
A class in Python is a blueprint for creating objects. It encapsulates data (attributes) and functions (methods) that operate on that data.

### Key Components of a Class:
* Attributes: Variables that hold data specific to the class or its objects.
* Methods: Functions defined inside a class that operate on its attributes.
* Constructor: A special method __init__ is used to initialize objects of the class.

### Example:
```
class Student:
    def __init__(self, name, age):
        self.name = name  # Attribute
        self.age = age

    def greet(self):  # Method
        return f"Hello, my name is {self.name} and I am {self.age} years old."

# Create an object of the class
student1 = Student("Alice", 20)
print(student1.greet())  # Output: Hello, my name is Alice and I am 20 years old.
```
## 2. User-Defined Modules
A module is a file containing Python code (functions, classes, or variables) that can be imported and reused in other programs. A user-defined module is a module created by the user.

### Creating a Module:
Write Python code in a .py file (e.g., mymodule.py).
Import the module in another Python script.

### Example:
Create a file called mymodule.py:

```
# mymodule.py
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b
```
Import and use it in another script:

```
import mymodule

result = mymodule.add(5, 3)
print(result)  # Output: 8

result = mymodule.subtract(5, 3)
print(result)  # Output: 2
```
### Benefits of Classes in Python
#### Encapsulation of Data and Methods:
Classes group related data (attributes) and functions (methods) together, providing a clear structure for complex programs and reducing redundancy.

C#### ode Reusability via Inheritance:
Classes support inheritance, allowing new classes to reuse and extend existing ones. This promotes efficient code reuse and reduces duplication.


#### Improved Maintainability and Scalability:
By encapsulating logic and creating reusable, modular code, classes make programs easier to maintain, debug, and scale as requirements grow.

### Benefits of Using Modules:
* Code reusability and better organization.
* Easier debugging and maintenance.
* Encapsulation of logic for clarity and scalability.

![Screenshot (359)](https://github.com/user-attachments/assets/a6b40071-4210-469b-931d-13196dccb2cc)

![Screenshot (364)](https://github.com/user-attachments/assets/8726c2a9-74d8-4145-9ef2-365aa2a5ecef)
