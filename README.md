# Week 6 Assignment: Safe Functions

## Files

- `safe_tools.py` — Contains three safe functions that handle division, number conversion, and dictionary lookups using `try` and `except`.

- `README.md` — Describes the assignment and explains how the functions handle errors.

## Why can't an `if` check catch `abc` on its own?

An `if` check can check whether input meets a condition, but it cannot automatically catch the `ValueError` raised when `int("abc")` tries to convert invalid text into an integer. Using `try` and `except ValueError` allows the program to handle the error and continue running instead of crashing.
