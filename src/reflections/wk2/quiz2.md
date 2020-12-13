# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, & const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a reusable set ofs statements that perform a task or calculation
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
Open/Closed
Liskov Substitution
Interface Segregation
Dependency Inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, because array indexes start with 0 at the first position
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (Math.floor(num % 2)){
  console.log(odd)
}
else{
  console.log(even)
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
 final-expression, i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, first accessed via index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, boolean, string, number, bigInt, symbol, object, function, null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
a parameter is a variable that is to be used within the function and an argument is the value for that variable that is passed in when the funtion is invoked.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are directly manipulated when accessed in a variable, and can be replaced with a different value. reference values on the other hand, when accessed in a variable, are altering the actual raw object that the value is referencing, meaning the value will change for any other variables that reference that same object.
```