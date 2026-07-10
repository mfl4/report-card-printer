# report-card-printer

A lightweight Python utility that demonstrates how student report card data is stored and validated. It showcases the core Python data types used to represent a student's record, including name, enrollment status, age, and score. And how to inspect and verify each value's type at runtime.

## Contents

| File           | Description                                                        |
| -------------- | ------------------------------------------------------------------ |
| `main.py`      | The program that defines report card fields and prints their types.|
| `LICENSE`      | CC0 1.0 Universal public domain dedication.                        |
| `.gitignore`   | Standard Python ignore rules for version control.                 |

## Getting started

1. Make sure you have Python 3 installed.
2. Run the program from the project folder:

   ```bash
   python main.py
   ```

## How it works

The script defines the fields of a report card, then prints each value alongside
its data type using the built-in `type()` function. It also uses `isinstance()`
to verify that a value belongs to an expected type.

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

- `name` is a **string** (`str`) holding the student's name `'Alice'`.
- `is_student` is a **boolean** (`bool`) indicating enrollment status (`True`).
- `age` is an **integer** (`int`) holding the value `20`.
- `score` is a **float** (`float`) holding the value `80.5`; `isinstance(score, float)`
  confirms that `score` belongs to the `float` type.

## Expected output

```
Alice <class 'str'>
True <class 'bool'>
20 <class 'int'>
True
80.5 <class 'float'>
```

## Key concepts

- Store report card fields in variables and assign appropriate values.
- Represent data with the `str`, `bool`, `int`, and `float` types.
- Use `print()` and `type()` to inspect values.
- Use `isinstance()` to check whether a value belongs to a given type.

## License

Released under [CC0 1.0](LICENSE), placing the work in the public domain.
