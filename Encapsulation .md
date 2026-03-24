# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Student:
    def __init__(self, name, marks):
        self.name = name          # public variable
        self.__marks = marks      # private variable

    # Getter method
    def get_marks(self):
        return self.__marks

    # Setter method
    def set_marks(self, marks):
        if marks >= 0 and marks <= 100:
            self.__marks = marks
        else:
            print("Invalid marks")


# Create object
s = Student("John", 85)

# Access public variable
print("Name:", s.name)

# Access private variable using method
print("Marks:", s.get_marks())

# Modify using setter
s.set_marks(90)
print("Updated Marks:", s.get_marks())
```
## Output
```
Name: John
Marks: 85
Updated Marks: 90
```
## Result
the code is verified.
