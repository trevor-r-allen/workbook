# Day 41
__02/15/2020__

## Thoughts on C# Data Types

### What are the three categories of data types? How are they different?
The three data types are value type, reference type, and pointer type. Value type variables contain values in their own memory, reference types contain an address that points to the location in memory where the value is actually stored, pointer types don't inherit from objects and can't be converted to/from them.

### What are the Value-type data types? What differences do you notice from JavaScript?
The value type data types are bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, and ushort.  Javascript matches as far as boolean and number, but also counts strings, null, and undefined among its value types.

### In your own words how do Reference types get stored in memory? How does this differ from Value types?
A value type gets stored directly to the memory address associated with the variable. A reference type gets stored to a memory address, which is then stored as the value in the memory address associated with the variable. 

#### Afternoon Lab: [C# RockPaperScissors Code](https://github.com/trevor-r-allen/csharp-rockpaperscissors)