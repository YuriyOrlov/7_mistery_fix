# Quadratic Equations Solver

This simple script solves simple quadratic equation, but mostly this program demonstrates work of unittest library.

Example of terminal output before fix:

```#!bash

$ python tests.py
.E..
======================================================================
ERROR: test_returns_none_for_complex_solution (__main__.QuadraticEquationTestCase)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "tests.py", line 22, in test_returns_none_for_complex_solution
    root1, root2 = get_roots(1, 2, 3)
  File "/home/yo_n/Projects/env35/devman/7_mistery_fix/quadratic_equation.py", line 6, in get_roots
    root1 = (-b - sqrt(discriminant)) / (2 * a)
ValueError: math domain error

----------------------------------------------------------------------
Ran 4 tests in 0.001s

FAILED (errors=1)

```

Example of terminal output after fix:

```#!bash
....
----------------------------------------------------------------------
Ran 4 tests in 0.000s

OK
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
