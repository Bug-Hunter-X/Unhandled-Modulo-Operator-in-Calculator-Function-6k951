# Unhandled Modulo Operator in JavaScript Calculator

This repository demonstrates a common yet easily overlooked error in JavaScript:  failure to handle all possible cases within a switch statement.

The `operate` function is intended to perform basic arithmetic operations (+, -, *, /). However, it lacks support for the modulo operator ('%'). This results in an error when the modulo operator is passed as an argument.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version.

## How to Reproduce the Bug

1. Clone this repository.
2. Run `bug.js` using Node.js (or a similar JavaScript environment).
3. Observe the error when calling `operate` with the modulo operator ('%').

## Solution

The solution involves adding a `case '%' `to the switch statement in `bugSolution.js` to handle modulo operations correctly.