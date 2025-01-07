# Javascript Bug: Handling undefined values

This repository demonstrates a common error in JavaScript related to handling undefined values and provides a solution.

The bug occurs when attempting to access the 'length' property of an undefined variable, which results in a `TypeError: Cannot read properties of undefined (reading 'length')` error.

## Bug
The `bug.js` file contains the buggy code. It tries to get the length of a variable `x`, but doesn't handle the case where `x` might be `undefined`.

## Solution
The `bugSolution.js` file demonstrates a corrected version of the code that explicitly checks for `undefined` before attempting to access the 'length' property. This prevents the error and handles the undefined case gracefully. 