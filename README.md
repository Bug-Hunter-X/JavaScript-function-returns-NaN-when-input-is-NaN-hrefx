# JavaScript NaN Handling Bug

This repository demonstrates a common bug in JavaScript related to NaN (Not a Number) handling and provides a solution.

The `bug.js` file contains a function `foo` that attempts to add two numbers. However, it doesn't explicitly handle the case where one or both of the inputs are NaN, resulting in NaN being returned. 

The `bugSolution.js` file shows the corrected function that uses `isNaN()` to check for NaN values and handles them appropriately, returning 0 in those cases.

This illustrates the importance of robust NaN handling in JavaScript to prevent unexpected results. 