# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
to define a scope
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class is a reference data type and struct is a value data type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
a declaration of the data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
the class from being instantiated on its own instead of through another class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
it allows the method to be overridden within classes that extend `Car`
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, abstract
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only code within the same class/struct
```