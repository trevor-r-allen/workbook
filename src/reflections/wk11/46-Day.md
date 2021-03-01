# Day 46
__02/22/2020__

## Thoughts on C# Inheritance

### What does Inheritance accomplish for us in C#?
Inheritance allows us to share code between a base class and a derived class. It also allows logical structuring of data via identity imprinting.

### How does Member inheritance work in C#? Does a class inherit all members of the base class?
Constructors and finalizers are not inherited. Otherwise, extending a base class as a derived class passes on all other members.

### How does accessibility affect inheritance?
Private members are inherited only if the child class is nested in the parent class. Protected members are only visible in derived classes, and internal members are visible in a derived class if located in the same assembly as the base class.

#### Afternoon Lab: [C# Vacation](https://github.com/trevor-r-allen/csharp-vacation)