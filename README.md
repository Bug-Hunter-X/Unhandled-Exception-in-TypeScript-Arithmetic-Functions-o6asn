# Unhandled Exception in TypeScript Arithmetic Functions

This repository demonstrates a common error in TypeScript: unhandled exceptions. The `divide` function throws an error if the denominator is zero, but the calling code doesn't handle this, resulting in a crash.  The solution showcases how to use `try-catch` to gracefully handle potential errors.

## Bug
The original code lacks error handling for the `divide` function, causing the program to terminate abruptly when division by zero occurs.

## Solution
The solution uses a `try-catch` block to handle the potential `Error` thrown by the `divide` function. This prevents the program from crashing and allows for more graceful error handling.