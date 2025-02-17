# JavaScript: Handling undefined values when accessing object properties

This repository demonstrates a common error in JavaScript: attempting to access properties of an undefined variable.  The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a corrected version.

The error occurs when the `foo` function in `bug.js` receives `undefined` as input.  Because the function attempts to access the `length` property, a `TypeError` is thrown.  The solution involves adding checks to handle `undefined` and `null` values before accessing object properties.

This example highlights the importance of defensive programming in JavaScript to prevent unexpected errors and improve code robustness.