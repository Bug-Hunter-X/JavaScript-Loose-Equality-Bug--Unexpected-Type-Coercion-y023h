# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (==) and how to fix it using strict equality (===).

## Description
JavaScript's loose equality operator (==) performs type coercion before comparison, leading to potential unexpected behavior.  Strict equality (===) avoids type coercion, providing more predictable results.

## Bug
The `bug.js` file contains code that uses loose equality, resulting in an unexpected outcome when null values are involved. 

## Solution
The `bugSolution.js` file demonstrates the corrected code, using strict equality (===) for more robust null value handling.

## How to Reproduce
1. Clone this repository.
2. Run `bug.js` and observe the output. 
3. Run `bugSolution.js` and compare the output. 
