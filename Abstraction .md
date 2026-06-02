# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
```
class Fish:
    def type(self):
        print("fish")

class Shark(Fish):
    def type(self):   # overriding method
        print("shark")

# Creating objects
obj_goldfish = Fish()
obj_hammerhead = Shark()

# Using loop
for animal in (obj_goldfish, obj_hammerhead):
    animal.type()
```

## OUTPUT
<img width="626" height="355" alt="image" src="https://github.com/user-attachments/assets/6560f063-9726-47ec-a257-268e0a03b540" />


## RESULT
Thus, the program successfully demonstrates method overriding, where the child class Shark overrides the type() method of the parent class Fish.
