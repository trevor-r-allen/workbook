# Day 16
__01/04/2020__

## Thoughts on Callback Hell

### What are some of the signs and causes of a 'Callback Hell'?
Visually you can see a large amount of closing brarckets and parenthesis directly following each other.  Also nested funtions and lack of error handling are potential causes.

### What does the asynchronous mean and how are callbacks involved?
Asynchronous means that some code will be delayed and the rest of the code can continue to run while its waiting.  Callbacks are the pending functions passed to the initial function, waiting to run when a result is ready.

### Summarize the 3 ways to avoid/fix 'Callback Hell'.
Name functionss, don't nest them in other functions, and make use of JS hoisting. Utilize modules, use exports instead of duplicating code, keep files small and uses specific. Plan for all errors to happen and ensure they're all handled.

#### Afternoon Lab: [Trivia API](https://trevor-r-allen.github.io/trivia-api/)
####                [Trivia API Code](https://github.com/trevor-r-allen/trivia-api)
