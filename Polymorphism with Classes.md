# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
class Beans:
    def type(self):
        return "Vegetable"

    def color(self):
        return "Green"


class Mango:
    def type(self):
        return "Fruit"

    def color(self):
        return "Yellow"


def display(obj):
    print("Type:", obj.type())
    print("Color:", obj.color())


b = Beans()
m = Mango()

display(b)
display(m)
```
## Output
Type: Vegetable
Color: Green
Type: Fruit
Color: Yellow
## Result
### Python Program

```python
class Beans:
    def type(self):
        return "Vegetable"

    def color(self):
        return "Green"


class Mango:
    def type(self):
        return "Fruit"

    def color(self):
        return "Yellow"


def display(obj):
    print("Type:", obj.type())
    print("Color:", obj.color())


b = Beans()
m = Mango()

display(b)
display(m)
```

### Output

```text
Type: Vegetable
Color: Green
Type: Fruit
Color: Yellow
```

**Result:**
Thus, the Python program to demonstrate **polymorphism** using the `Beans` and `Mango` classes and a generic function was successfully executed.
