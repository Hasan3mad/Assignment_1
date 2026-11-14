2. Essay Questions

1. What is the difference between forEach and for...of? When would you use each?

forEach() is used to loop through all elements in an array and execute a function for each element. But we cannot use break or continue with it.
for...of is used to loop through elements in arrays and other iterable objects. We can use break and continue with it.

===============================================

2. What is hoisting and what is the Temporal Dead Zone (TDZ)? Explain with examples.

Hoisting means that JavaScript handles variable and function declarations before executing the code. This allows some variables and functions to be used before their declaration.
The Temporal Dead Zone (TDZ) is the time before a let or const variable is declared and initialized. If we try to use it during this time, JavaScript gives us a ReferenceError.

================================================

3. What are the main differences between == and ===?

The == operator compares two values and can change their types automatically before comparing them.
The === operator compares both the value and the data type without changing the types.

================================================

4. Explain how try-catch works and why it is important in async operations.

try-catch is used to handle errors in JavaScript.
The try block contains the code that may cause an error, and the catch block handles the error if something goes wrong.
It is important in async operations because it helps us handle errors from rejected Promises when using async and await.

================================================

5. What’s the difference between type conversion and coercion? Provide examples of each.

Type conversion means changing a data type manually using methods like Number() or String().
Type coercion means JavaScript changes the data type automatically during an operation.