# Unexpected String Concatenation in JavaScript
This example demonstrates a common error in JavaScript where the '+' operator performs string concatenation instead of numerical addition when one of the operands is a string. This behavior is due to JavaScript's dynamic typing system.

## Bug Report
The function `foo` is intended to add two numbers. However, when one or both inputs are strings, it performs string concatenation, resulting in unexpected output.

## Solution
The solution involves explicit type checking or conversion to ensure both operands are numbers before performing addition. 