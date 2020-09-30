# Prototype

- Helps to copy existing objects without making the code dependent on their classes
- Aims to reeduce the number of classes required by an application.
- Instead of relying on subclasses, it creates object by copying a prototype instance at run-time.

## Why use this pattern?

- Consider you have an object in your code and you want to create a copy of it. But the object may have some private attributes and methods that may not be visible by directly inspecting the object. This also creates a dependency problem with that class as well.

- `Prototype` pattern tries to solve this problem by delegating the cloning process. All the objects that support cloning must have a common interface usually just `clone()` method that will let you clone an object withouth couppling your code to that object.

- An object that supports cloning is called a `prototype`. When objects have numbers of fields and configurations, clonining can be a good alternative to sub-classing.

- This pattern will actually reduce the number of subclasses that only differ in the way they are initialized. Like the devs should create the subclass just to be able to create object with a required configuration.

## Advantages

- Provides alternative to inheritance.

- Provides clonning of objects without coupling classes.

## Disadvantages

- Cloning complex objects can be tedious.

