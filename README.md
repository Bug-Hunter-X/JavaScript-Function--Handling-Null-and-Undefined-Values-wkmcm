# JavaScript Function: Handling Null and Undefined Values

This repository demonstrates a common JavaScript bug related to handling null and undefined values in a function and presents a solution.

## Bug Description
The `foo` function adds two numbers. It correctly handles `null` values. However, it fails to explicitly handle `undefined` values, resulting in `NaN` when an argument is undefined.

## Solution
The solution enhances the function to explicitly check for `undefined` values using the loose equality operator (==) and handles them appropriately.  Strict equality (===) is used to handle null values as in original code.