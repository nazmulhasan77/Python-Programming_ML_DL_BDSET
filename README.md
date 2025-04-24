
# 🐍 Basic Python & Popular Libraries

## 📌 Python Basics

### Variables & Data Types
```python
x = 10          # Integer
y = 3.14        # Float
name = "Alice"  # String
is_active = True # Boolean
```

### Data Structures
```python
# List
fruits = ["apple", "banana", "cherry"]

# Tuple
coordinates = (10.0, 20.0)

# Set
unique_items = {1, 2, 3}

# Dictionary
person = {"name": "Alice", "age": 25}
```

### Conditionals
```python
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is 5")
else:
    print("x is less than 5")
```

### Loops
```python
# For loop
for item in fruits:
    print(item)

# While loop
i = 0
while i < 5:
    print(i)
    i += 1
```

### Functions
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Bob"))
```

---

## 📚 Common Python Libraries

### ✅ NumPy – Numerical Computation
```python
import numpy as np

arr = np.array([1, 2, 3])
print(np.mean(arr))  # Mean of array
```

### ✅ Pandas – Data Analysis
```python
import pandas as pd

data = {'name': ['Alice', 'Bob'], 'age': [25, 30]}
df = pd.DataFrame(data)
print(df.head())
```

### ✅ Matplotlib – Plotting
```python
import matplotlib.pyplot as plt

x = [1, 2, 3]
y = [4, 5, 6]
plt.plot(x, y)
plt.title("Line Graph")
plt.show()
```

### ✅ Seaborn – Statistical Data Visualization
```python
import seaborn as sns
import pandas as pd

df = sns.load_dataset("iris")
sns.pairplot(df, hue="species")
```

### ✅ Scikit-learn – Machine Learning
```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
# Assume X_train and y_train are defined
# model.fit(X_train, y_train)
```

### ✅ Requests – HTTP Requests
```python
import requests

response = requests.get("https://api.github.com")
print(response.status_code)
```

### ✅ OS & Pathlib – File System Operations
```python
import os
from pathlib import Path

print(os.getcwd())  # Current working directory
file = Path("test.txt")
file.write_text("Hello!")
```

---

## 🎯 Summary
- Python is versatile for web, data science, automation, and more.
- Libraries make Python extremely powerful and easy to use.

Happy Coding! 🚀
