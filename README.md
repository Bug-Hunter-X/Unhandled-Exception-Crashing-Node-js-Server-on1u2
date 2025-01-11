# Unhandled Exception Crashing Node.js Server

This repository demonstrates a common error in Node.js applications: unhandled exceptions that lead to server crashes.  The `bug.js` file shows a server that throws an unhandled exception, causing it to terminate unexpectedly. The solution, in `bugSolution.js`, demonstrates how to properly handle exceptions using `try...catch` blocks to prevent crashes and gracefully handle errors.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository directory in your terminal.
3. Run `node bug.js`. Observe that the server crashes immediately after throwing an error.
4. Run `node bugSolution.js`. Observe that the server handles the error gracefully and does not crash, instead logging the error to the console.