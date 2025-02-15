# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  Specifically, the example shows a route that retrieves a user by ID.  If the ID is not a valid number, the code crashes without any proper error handling.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version with improved error handling.