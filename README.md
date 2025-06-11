# matrix-math-group21

`matrix-math-group21` is a simple Python library for performing matrix **addition** and **multiplication** using 2D lists. It is lightweight, dependency-free, and beginner-friendly.

---

## ✅ Features

- Add two matrices of the same dimensions
- Multiply two compatible matrices
- Includes input validation with helpful error messages
- Written in pure Python (no external libraries required)

---

## 📦 Installation

You can install the package from [PyPI](https://pypi.org/project/matrix-math-group21/) using `pip`:

```bash
pip install matrix-math-group21
```

> Make sure you have Python 3.7 or higher installed.

---


## 🚀 How to Use

### Step 1: Import the Library

```python
from matrix_math_group21 import add_matrices, multiply_matrices
```

### Step 2: Define Your Matrices (as 2D lists)

```python
matrix_a = [
    [1, 2],
    [3, 4]
]

matrix_b = [
    [5, 6],
    [7, 8]
]
```

### Step 3: Use the Functions

#### ➕ Add Two Matrices

```python
result = add_matrices(matrix_a, matrix_b)
print(result)  # Output: [[6, 8], [10, 12]]
```

#### ✖️ Multiply Two Matrices
```python
result = multiply_matrices(matrix_a, matrix_b)
print(result)  # Output: [[19, 22], [43, 50]]
```

---

## ⚠️ Error Handling

- If matrices in `add_matrices` do **not** have the same shape, a `ValueError` is raised. e.g "Marvin you know how matrixes work please try again, make sure they are the same dimensions this time"
- If matrices in `multiply_matrices` are **not compatible**, a `ValueError` is raised. e.g "You're not a quality tester please make sure the number of columns match the rows, Marvin"

---

## 👤 Author

Built by **Group 21** as a learning project.
```python
result = multiply_matrices(matrix_a, matrix_b)
print(result)  # Output: [[19, 22], [43, 50]]
```

---
