# Unhandled Promise Rejection in Node.js

This repository demonstrates a common error in Node.js applications: unhandled promise rejections.  The `bug.js` file contains an Express.js app with an asynchronous function that may throw an error.  The error is not properly handled, leading to a potential crash.  The `bugSolution.js` file provides a corrected version with proper error handling.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `node bug.js`.
4. Observe the behavior (it may crash or produce an unhandled promise rejection warning).
5. Run `node bugSolution.js` to see the corrected version.

## Key Learning

Always handle promise rejections using `.catch()` to prevent unexpected behavior and crashes in your Node.js applications.