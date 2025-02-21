# Express.js Route Handler Error: Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  lack of error handling for invalid input parameters.

The `bug.js` file contains a route handler that retrieves a user by ID.  It attempts to parse the ID as an integer but fails to handle cases where the ID is not a valid integer, causing the application to crash or behave unexpectedly.

The `bugSolution.js` file provides a corrected version of the route handler with proper error handling.