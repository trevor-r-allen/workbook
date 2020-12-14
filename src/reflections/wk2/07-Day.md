# Day 7
__12/08/2020__

## Thoughts on JavaScript Functions

### What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
Function declarations are hoisted and if they return something it will return to wherever it is invoked. Function expressions are not hoisted, can be anonymous and stored to a variable, in which case when invoked the return will be stored for access in the variable.
Arrow functions have shorter syntax and do not create their own 'this' value, useful for inline or within methods.

### What is the difference between parameters and arguments?
Parameters are a variables that are to be used within the function. Arguments are the given values for those variables that are passed in when the funtion is invoked.

### What are higher order functions? Give an example.
Higher order functions are functions that accept other funtions as parameters or returns another function. Methods like forEach, filter, and sort are examples of higher order functions.