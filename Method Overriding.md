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
class Fish:
    def type(self):
        print("Fish is an aquatic animal")


class Shark(Fish):
    def type(self):
        print("Shark is a large fish")


f = Fish()
s = Shark()

f.type()
s.type()
```
## OUTPUT
Fish is an aquatic animal
Shark is a large fish
## RESULT
### Python Program

```python
class Fish:
    def type(self):
        print("Fish is an aquatic animal")


class Shark(Fish):
    def type(self):
        print("Shark is a large fish")


f = Fish()
s = Shark()

f.type()
s.type()
```

### Output

```text
Fish is an aquatic animal
Shark is a large fish
```

**Result:**
Thus, the Python program demonstrating **class inheritance** and **method overriding** using `Fish` and `Shark` was successfully executed.
