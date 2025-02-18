# MATLAB Empty Array Input Handling Bug

This repository demonstrates a common error in MATLAB functions: unexpected behavior or errors when an empty array is passed as input.  The `bug.m` file shows the function with the faulty logic, and `bugSolution.m` shows the corrected version.

## Problem
The original function `myFunction` does not properly handle the case when an empty array is provided as input. This leads to unexpected results or runtime errors.

## Solution
The solution adds explicit checks for empty arrays and handles them appropriately. This ensures the function operates correctly regardless of the input type.

## Usage
1. Clone or download this repository.
2. Open MATLAB and navigate to the directory.
3. Run `bug.m` and `bugSolution.m` to see the difference in behavior with empty array input.