# TypeScript Off-by-one Error

This repository demonstrates a common off-by-one error in TypeScript when iterating over arrays.

The `bug.ts` file contains code with the error.  The `bugSolution.ts` file provides the corrected code.

## Bug

The original code attempts to print the elements of an array using a `for` loop.  However, the loop condition `i <= arr.length` causes an error because the last valid index of an array is `arr.length - 1`.

## Solution

The solution modifies the loop condition to `i < arr.length`, correctly iterating through all elements of the array without causing an error.

This example highlights the importance of careful array indexing in programming.