# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numerical field by a specified value.  Using a string instead will lead to an error.

## Bug
The `bug.js` file contains the incorrect code that attempts to increment a field using a string value with the `$inc` operator.

## Solution
The `bugSolution.js` file provides the corrected code.  The string value is replaced with a numerical value to properly increment the field.
