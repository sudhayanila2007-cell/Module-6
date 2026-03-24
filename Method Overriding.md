# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```
# Parent Class
class Fish:
    def swim(self):
        print("Fish can swim")

    def habitat(self):
        print("Fish lives in water")


# Child Class
class Shark(Fish):
    # Overriding method
    def swim(self):
        print("Shark swims very fast")


# Create objects
f = Fish()
s = Shark()

# Call methods
f.swim()
s.swim()   # overridden method
s.habitat()  # inherited method
```
## OUTPUT
```
Fish can swim
Shark swims very fast
Fish lives in water
```
## RESULT
the code is verified.
