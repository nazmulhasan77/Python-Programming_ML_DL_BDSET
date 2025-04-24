
# 🐍 Basic Python Cheat Sheet

A simple and clean guide to the most common Python basics. Perfect for beginners!

---

## 🔹 Variables & Data Types
```python
x = 10              # Integer
name = "Alice"      # String
price = 19.99       # Float
is_active = True    # Boolean
```

## 🔹 Lists
```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])           # "apple"
fruits.append("orange")    # Add item
```

## 🔹 Dictionaries
```python
person = {"name": "Bob", "age": 25}
print(person["name"])      # "Bob"
person["age"] = 26
```

## 🔹 Conditionals
```python
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is 5")
else:
    print("x is less than 5")
```

## 🔹 Loops
```python
# For loop
for fruit in fruits:
    print(fruit)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1
```

## 🔹 Functions
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))  # Hello, Alice!
```

## 🔹 Classes
```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} says woof!")

my_dog = Dog("Buddy")
my_dog.bark()  # Buddy says woof!
```

## 🔹 Input/Output
```python
name = input("Enter your name: ")
print("Hello,", name)
```

## 🔹 File Handling
```python
# Writing to a file
with open("hello.txt", "w") as file:
    file.write("Hello, world!")

# Reading from a file
with open("hello.txt", "r") as file:
    content = file.read()
    print(content)
```
