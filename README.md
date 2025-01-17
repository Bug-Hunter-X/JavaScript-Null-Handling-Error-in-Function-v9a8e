# JavaScript Null Handling Error

This repository demonstrates a common JavaScript error related to handling `null` values within functions. The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.  The problem arises from attempting to perform arithmetic operations on potentially `null` values without proper checking.

## Bug Description:
The function `foo` adds two numbers. However, it crashes if either input is `null`. The solution adds a check to return `null` if either input is `null`.