# report-card-printer

A small Python workshop project from the **Python Basics** course. This folder
contains a hands-on exercise that introduces fundamental Python concepts:
variables and data types.

## Contents

| File           | Description                                                        |
| -------------- | ------------------------------------------------------------------ |
| `main.py`      | The sample program that demonstrates variables and their types.    |
| `LICENSE`      | CC0 1.0 Universal public domain dedication.                        |
| `.gitignore`   | Standard Python ignore rules for version control.                 |

## Getting started

1. Make sure you have Python 3 installed.
2. Run the program from the project folder:

   ```bash
   python main.py
   ```

## What `main.py` does

The script shows how to store values in variables and inspect their data type
using the built-in `type()` function and the `isinstance()` check.

```python
name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))

age = 20
print(age, type(age))

score = 80.5
print(isinstance(score, float))
print(score, type(score))
```

- `name` is a **string** (`str`) holding the text `'Alice'`.
- `is_student` is a **boolean** (`bool`) holding the value `True`.
- `age` is an **integer** (`int`) holding the value `20`.
- `score` is a **float** (`float`) holding the value `80.5`; `isinstance(score, float)`
  confirms that `score` belongs to the `float` type.

Running the program prints each value together with its type:

```
Alice <class 'str'>
True <class 'bool'>
20 <class 'int'>
True
80.5 <class 'float'>
```

## Learning goals

- Declare variables and assign values.
- Recognize the `str`, `bool`, `int`, and `float` data types.
- Use `print()` and `type()` to explore values.
- Use `isinstance()` to check whether a value belongs to a given type.

## License

Released under [CC0 1.0](LICENSE), placing the work in the public domain.
