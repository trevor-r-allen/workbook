# Day 17
__01/05/2020__

## Thoughts on JS Promises

### What are the three states of a `promise`?
Pending is the state while waiting for the response before passing or failing.  After the response, depending on if the `promise`'s condition is met, the state will be either resolved or rejected.

### How do `promise`s seek to resolve the issues of 'Callback Hell'?
They introduce the chaining feature which allows callbacks to be attatched to functions instead of passed into them. This makes the code look cleaner and easier to read.

### What is the difference between `.then()` and `.catch()`?
`.then()` is used when the `promise`'s state is resolved. `.catch()` is used when the `promise`'s state is rejected.


#### Afternoon Lab: [API Gregslist](https://trevor-r-allen.github.io/winter2020-api-gregslist/)
####                [API Gregslist Code](https://github.com/trevor-r-allen/winter2020-api-gregslist)
