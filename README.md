# Unexpected Type Coercion in JavaScript Addition

This repository demonstrates a common JavaScript bug related to type coercion. When adding a number and a string using the + operator, JavaScript performs string concatenation instead of numerical addition. This can lead to unexpected results and errors.

## Bug Description
The `foo` function attempts to add a number and a string. JavaScript implicitly coerces the number to a string, resulting in string concatenation instead of the expected numerical sum.

## Solution
The solution involves explicitly converting the string to a number using `parseInt()` or `parseFloat()` before performing the addition.  This ensures that the addition operation is performed correctly.
