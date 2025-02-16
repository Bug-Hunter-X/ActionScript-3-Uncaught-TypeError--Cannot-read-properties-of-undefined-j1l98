# ActionScript 3 Uncaught TypeError: Cannot read properties of undefined

This repository demonstrates a common ActionScript 3 error and its solution. The error, "Uncaught TypeError: Cannot read properties of undefined (reading 'someVariable')", occurs when you attempt to access a variable that hasn't been properly initialized or is out of scope.

## Bug

The `bug.as` file contains code that attempts to access an undefined variable, leading to the TypeError.  This is a frequent issue in ActionScript and many other programming languages.  Proper variable initialization and scope management are crucial to preventing this.

## Solution

The `bugSolution.as` file presents a corrected version of the code. It demonstrates the importance of initializing variables before using them, ensuring the variable is within the correct scope, or handling potential undefined values using conditional checks (e.g., if statements or try/catch blocks).