# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion.  The function `foo` is intended to add two numbers, but due to type coercion, it performs string concatenation when one of the arguments is a string.

## Bug Description

The `foo` function takes two arguments and should return their sum. However, if one argument is a string, the `+` operator performs string concatenation instead of numerical addition. This leads to unexpected results.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the code using Node.js (or your preferred JavaScript environment).
4. Observe the unexpected output.

## Solution

The `bugSolution.js` file provides a corrected version of the `foo` function using type checking or explicit type conversion to ensure that numerical addition is always performed.