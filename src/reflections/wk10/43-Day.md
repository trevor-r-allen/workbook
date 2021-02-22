# Day 43
__02/17/2020__

## Thoughts on C# Enums

### What is an Enum, and what are some use cases for them?
Enums are unique value data types that are used to assign symbolic names to values. An example use case is using Enum to name the days of the week while the values still represent the number.

### How can you modify an Enum?
You can change the base type of enum when declaring it, which is `int` by default. You can also alter the default values of the members of an enum, with the first member's value defaulting to 0.

### How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)
When setting up a `GET` request, IEnumerable is used to declare the items in the array returned as the data type of a specific model.

#### Afternoon Lab: [C# GregsList Code](https://github.com/trevor-r-allen/csharp-gregslist)