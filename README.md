# Quadratic Equations Solver

`quadratic_equation.py` contains the function `get_roots()` that solves the quadratic equations for real roots with given coefficients:

1. It returns `None` for the complex solution
2. It returns `None` for second root, if the equation has only one solution
3. If the equation has two roots, second root is bigger than first.

# How to use

The module requires installed Python 3.5 interpreter.
Use the module by importing the whole module: 
```
import quadratic_equation
```

or the function `get_roots()` from it:

```
import get_roots from quadratic_equation
```

# Test

It is successfully tested with `tests.py`:
```
$ python3 tests.py
....
----------------------------------------------------------------------
Ran 4 tests in 0.000s

OK
```


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
