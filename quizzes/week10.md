# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The purpose of a namespace is to provide a way to group related classes, structs, and interfaces, and to avoid naming conflicts between different sets of related code.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```

A class is a reference type, while a struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Constructor.
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
String is the return type of the Start() method, indicating that the method returns a string value.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract in the class definition is preventing the Car class from being instantiated directly.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The purpose of the virtual is to allow the method Start() to be overridden in derived classes.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, protected, internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only other members of that class can access it.
```