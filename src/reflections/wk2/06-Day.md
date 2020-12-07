# Day 6
__12/07/2020__

## Thoughts on JavaScript Variables

### What is scope?
Scope indicates in what areas of the code a variable can be used based on where it was declared and not all scopes are available to all types of variables. Examples being global for use everywhere, function/local for use only within the function it was declared in, and block for use only within the same set of curly brackets it was declared in.

### What is hoisting?
Hoisting is the process by which variable and function declarations are moved to the top of their scope. This happens before code execution and essentially means that a variable may still be referenced above where it is located. It is important to note that only the declaration is hoisted and not the value stored in it, if one was. 

### In what cases might I use let vs. const vs. var?
Const is useful if you want to be able to reference a variable and don't want to change it. Var is useful if you want to globally declare a variable and be able to reference and modify it within conditionals and functions. This isn't always a desired behavior however and that is where const and let come in, with let being capable of having its value changed. Having a block scope, as stated above, they allow for more controlled and compartmentalized usage.