# Unexpected Behavior in CSS calc() Due to Spaces Around Operators

This repository demonstrates an uncommon error related to the use of spaces in the `calc()` function within CSS.  Incorrect spacing around operators can lead to unexpected behavior or parsing errors.

## Problem
Spaces around operators (+, -, *, /) inside `calc()` are often overlooked and cause the calculation to fail silently.

## Solution
Remove any unnecessary spaces surrounding the mathematical operators within the `calc()` function.  Maintain proper concatenation of units and values. 

## How to reproduce the bug
1. Open `bug.css`
2. Observe the incorrect usage of `calc()`
3. Run the CSS in a browser to see the unexpected output

## How to fix the bug
1. Open `bugSolution.css`
2. Observe the correct usage of `calc()` with no spaces around the operators
3. Run the CSS in a browser to see the intended output