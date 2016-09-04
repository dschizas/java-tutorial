# Programming language: Java

1. [Object oriented programming](#object-oriented-programming)
2. [OOP Concepts](#concepts)
3. [Immutable Objects](#immutable-objects)

## Object oriented programming
Object-oriented programming is a method of programming based on a hierarchy of classes, and well-defined and cooperating objects.

## Concepts
### Object
An object is a software bundle of related state and behavior. Software objects are often used to model the real-world objects that you find in everyday life.

### Class
A class is a blueprint or prototype from which objects are created.

### Inheritance
Inheritance provides a powerful and natural mechanism for organizing and structuring your software.

### Interface
An interface is a contract between a class and the outside world. When a class implements an interface, it promises to provide the behavior published by that interface.

### Package
A package is a namespace for organizing classes and interfaces in a logical manner. Placing your code into packages makes large software projects easier to manage.

## Immutable objects
An object is considered immutable if its state cannot change after it is constructed.

Immutable objects are particularly useful in concurrent applications. Since they cannot change state, they cannot be corrupted by thread interference or observed in an inconsistent state.

Programmers are often reluctant to employ immutable objects, because they worry about the cost of creating a new object as opposed to updating an object in place. The impact of object creation is often overestimated, and can be offset by some of the efficiencies associated with immutable objects. These include decreased overhead due to garbage collection, and the elimination of code needed to protect mutable objects from corruption.
