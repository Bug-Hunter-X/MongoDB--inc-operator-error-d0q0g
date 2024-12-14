# MongoDB $inc Operator Error

This repository demonstrates an uncommon error related to the MongoDB `$inc` operator. The error occurs when attempting to increment a field using a string value instead of a numeric value.

## Bug
The provided `bug.js` file shows incorrect usage of the `$inc` operator. It tries to increment the `counter` field by '1' (a string), leading to an unexpected behavior or an error. 

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator, using the numeric value 1 for the increment operation. 
