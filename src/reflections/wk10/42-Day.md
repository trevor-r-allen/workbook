# Day 42
__02/16/2020__

## Thoughts on C# Lists 

### What is a List in C#?
A List is a collection of values of a certain data type.  Lists have several methods that can be used on the collection.

### What List methods seem like you might use them often? Why?
List.Find or List.FindAll would often be useful to access a particular piece(s) of data, perhaps comparing based on the value of a class' property.  Also, List.ForEach to modify all items of a list in the same way.

### How would you retrieve an item from a list? What method could you use?
Using a List.Find method and storing the returned value to a new variable. Eg. `Obj item = list.Find(obj => obj.Name == "Trevor");`

#### Afternoon Lab: [C# Petshop Code](https://github.com/trevor-r-allen/winter20-petshop)