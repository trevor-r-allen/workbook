# Day 18
__01/06/2020__

## Thoughts on JS Async and Await

### What is the purpose of `async`/`await`?
To reduce the syntax complexity of promises even further. Also, to overcome the limitations of promise chaining.

### What must you do in order to `await` a promise inside of a function?
The function must be prepended with `async` in order to have it return a promise. This enables the proper use of `await` within the function.

### What are some of the primary benefits of `async`/`await`?
One main benefit is the code is cleaner and easier to read. In addition, chaining is easier and much more eradable than with promises, and debugging is also easier because the compiler treats `async`/`await` as synchronous code.

#### Afternoon Lab: [Pokedex API ](https://trevor-r-allen.github.io/pokedex-api/)
####                [Pokedex API Code](https://github.com/trevor-r-allen/pokedex-api)
