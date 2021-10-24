# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A name space is the title of your app plus what that file is ex controller service repo. They make it so that file is tied to those types of files so that you can use it in other files by adding using (name of app).(whatever type it is).
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class is the reference type Struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void tells the method that it isnt returning anything.
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
the type of data that the method should return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
An abstract class is used to create a base class that can be commonly accessed by several derived classes. The abstract class has to be inherited by sub classes.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
A virtual allows a method to be overwritten in a subclass or child class. It can be over written to match the needs of the child class or it can remain the same as the parent class and be used as its original function.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private internal protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
everything but child classes  can access that method. A child class would not be able to though because it is not inherited if it is private. If the child class is NESTED inside of the parent it would be able to use it. That is the only exception.
```