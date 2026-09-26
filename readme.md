# Python Calculator

This repository contains a simple Python calculator with basic arithmetic functions:

- `add(a, b)`
- `subtract(a, b)`
- `multiply(a, b)`
- `divide(a, b)`

The `divide` function raises a `ValueError` when dividing by zero.

## Usage

```python
from calculator import add, divide, multiply, subtract

print(add(2, 3))
print(subtract(5, 1))
print(multiply(4, 2))
print(divide(10, 2))
```

## Running tests

```bash
pytest
```
