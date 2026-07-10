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
using the built-in `type()` function.

```python
name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))
```

- `name` is a **string** (`str`) holding the text `'Alice'`.
- `is_student` is a **boolean** (`bool`) holding the value `True`.

Running the program prints each value together with its type:

```
Alice <class 'str'>
True <class 'bool'>
```

## Learning goals

- Declare variables and assign values.
- Recognize the `str` and `bool` data types.
- Use `print()` and `type()` to explore values.

## License

Released under [CC0 1.0](LICENSE), placing the work in the public domain.
