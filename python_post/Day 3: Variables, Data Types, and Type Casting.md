## 🐍 Day 3: Variables, Data Types, and Type Casting 

Welcome to **Day 3** of our Python journey! Today, we’ll dive into variables, data types, and type casting. These are fundamental concepts that form the backbone of Python programming. Let’s get started! 🎉

---

### 🔹 Variables in Python

Variables are used to store data in Python. You don’t need to declare the type of a variable explicitly; Python infers it automatically.

#### Example:

```python
# Assigning values to variables
name = "Alice"  # String
gender = 'F'      # Character
age = 25          # Integer
height = 5.6      # Float
is_student = True # Boolean

# Printing variables
print(name, gender, age, height, is_student)
```

#### Rules for Naming Variables:
1. Variable names must start with a letter or an underscore (_).
2. They cannot start with a number.
3. Variable names can only contain alphanumeric characters and underscores.
4. Variable names are case-sensitive.

---

### 🔹 Data Types in Python

Python has several built-in data types. Here are the most commonly used ones:

| Data Type   | Example         |
|-------------|-----------------|
| `int`       | `10`, `-5`      |
| `float`     | `3.14`, `-0.01` |
| `str`       | `'Hello'`, `"World"` |
| `bool`      | `True`, `False` |
| `list`      | `[1, 2, 3]`     |
| `tuple`     | `(1, 2, 3)`     |
| `dict`      | `{"key": "value"}` |
| `set`       | `{1, 2, 3}`     |

#### Example:

```python
# Different data types
x = 10          # int
y = 3.14        # float
z = "Python"   # str
is_active = True # bool

# Printing data types
print(type(x))
print(type(y))
print(type(z))
print(type(is_active))
```

---

### 🔹 Type Casting

Type casting is the process of converting one data type to another. Python provides several built-in functions for type casting:

| Function    | Description                     |
|-------------|---------------------------------|
| `int()`     | Converts to an integer          |
| `float()`   | Converts to a floating-point    |
| `str()`     | Converts to a string            |
| `bool()`    | Converts to a boolean           |
| `list()`    | Converts to a list              |
| `tuple()`   | Converts to a tuple             |

#### Example:

```python
# Type casting examples
num_str = "123"
num_int = int(num_str)  # Convert string to int

pi = 3.14
pi_str = str(pi)        # Convert float to string

is_valid = "True"
is_valid_bool = bool(is_valid)  # Convert string to boolean

print(num_int, type(num_int))
print(pi_str, type(pi_str))
print(is_valid_bool, type(is_valid_bool))
```

---

### 🔹 Dynamic Typing in Python

Python is dynamically typed, meaning you can reassign variables to different data types:

#### Example:

```python
x = 10       # int
x = "Hello" # str
x = 3.14     # float
print(x)
```

---

### 🎯 Conclusion

Today, we explored variables, data types, and type casting in Python. These concepts are essential for writing efficient and error-free code. Practice these examples and experiment with different data types to solidify your understanding. See you on Day 4! 🚀