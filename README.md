# TypeScript Type Error: Adding Number and String

This repository demonstrates a common type error in TypeScript where a function expecting number parameters receives a string.  The goal is to highlight the importance of careful type checking to prevent such runtime errors.

## Bug
The `add` function is defined to accept two numbers and return their sum. However, the code attempts to call `add` with a number and a string, resulting in a type error at compile time. This demonstrates the basic type safety mechanisms in TypeScript.

## Solution
The solution involves ensuring that both parameters passed to `add` are indeed numbers.  Type checking and input validation can prevent this type of error from occurring in production code.

## How to reproduce
1. Clone the repository.
2. Compile the `bug.ts` file using the TypeScript compiler (tsc). The compiler will report a type error.
3. Run `bugSolution.ts` to see how the error can be avoided.