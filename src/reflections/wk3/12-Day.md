# Day 12
__12/15/2020__

## Thoughts on Encapsulation in JS

### What is the purpose of Encapsulation?
Encapsulation is meant to keep data from being accessed from outside its own capsule. This is beneficial from a security standpoint, as well as creates more efficiency, organization, and flexibility.

### What were some of the problems with closures and the underscore prefix?
Since the underscore prefix was merely an agreed upon convention, it was often disregarded and unenforced. True encapsulation properly restricts access to the data.

### How do we create private variables in an ES6 Class? Why would we do this?
In an ES6 class you would use a constructor and any variables defined within are limited to that scope. This would be done to prevent direct manipulation of the variable while setting up priviledged functions with reference-based access to manipulate the variable.

#### Afternoon Lab: [VendrrMachine](https://trevor-r-allen.github.io/vendrrr-machine/)
