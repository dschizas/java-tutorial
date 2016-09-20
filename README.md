# Programming language: Java

1. [Object oriented programming](#object-oriented-programming)
2. [OOP Concepts](#concepts)
3. [Design Patterns](#design-patterns)
4. [Immutable Objects](#immutable-objects)
5. [Processes and Threads](#processes-and-threads)
6. [Lambda Expressions](#lambda-expressions)

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

## Design Patterns
In the simplest terms, such a common solution is a design pattern and the repository or place of reference that contains such patterns is a design-pattern catalog. A design pattern prescribes a proven solution from experienced hands for a recurring design problem. Apart from describing the problem and prescribing the solution, the pattern will also explain the implementation issues involved and consequences, if any, of using the pattern. These solutions are generic in nature. They are described in the well-defined "Pattern Templates"; the most common one in use is the template defined by the "Gang of Four." The pattern templates usually have a name that offers a good idea as to what that pattern is all about, followed by where the pattern is applicable, the motivation, implementation issues, and other descriptions.

Use of such patterns makes the design of an application transparent. These patterns have been used successfully by developers in their respective work and hence the pros and cons of their use as well as implementation issues are known beforehand. All design patterns are reusable and can be adapted to a particular context; this gives developers flexibility.

### Examples
1. Singleton Pattern

  Singleton pattern is one of the simplest design patterns in Java. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.

  This pattern involves a single class which is responsible to create an object while making sure that only single object gets created. This class provides a way to access its only object which can be accessed directly without need to instantiate the object of the class.

2. MVC Pattern

  MVC Pattern stands for Model-View-Controller Pattern. This pattern is used to separate application's concerns.

  Model - Model represents an object or JAVA POJO carrying data. It can also have logic to update controller if its data changes.

  View - View represents the visualization of the data that model contains.

  Controller - Controller acts on both model and view. It controls the data flow into model object and updates the view whenever data changes. It keeps view and model separate.

## Immutable objects
An object is considered immutable if its state cannot change after it is constructed.

Immutable objects are particularly useful in concurrent applications. Since they cannot change state, they cannot be corrupted by thread interference or observed in an inconsistent state.

Programmers are often reluctant to employ immutable objects, because they worry about the cost of creating a new object as opposed to updating an object in place. The impact of object creation is often overestimated, and can be offset by some of the efficiencies associated with immutable objects. These include decreased overhead due to garbage collection, and the elimination of code needed to protect mutable objects from corruption.

## Processes and Threads
In the Java programming language, concurrent programming is mostly concerned with threads. However, processes are also important.

A computer system normally has many active processes and threads. This is true even in systems that only have a single execution core, and thus only have one thread actually executing at any given moment. Processing time for a single core is shared among processes and threads through an OS feature called time slicing.

It's becoming more and more common for computer systems to have multiple processors or processors with multiple execution cores. This greatly enhances a system's capacity for concurrent execution of processes and threads — but concurrency is possible even on simple systems, without multiple processors or execution cores.

### Threads
Threads are sometimes called lightweight processes. Both processes and threads provide an execution environment, but creating a new thread requires fewer resources than creating a new process.

Threads exist within a process — every process has at least one. Threads share the process's resources, including memory and open files. This makes for efficient, but potentially problematic, communication.

Multithreaded execution is an essential feature of the Java platform. Every application has at least one thread — or several, if you count "system" threads that do things like memory management and signal handling. But from the application programmer's point of view, you start with just one thread, called the main thread. This thread has the ability to create additional threads.

## Lambda expressions
One issue with anonymous classes is that if the implementation of your anonymous class is very simple, such as an interface that contains only one method, then the syntax of anonymous classes may seem unwieldy and unclear. In these cases, you're usually trying to pass functionality as an argument to another method, such as what action should be taken when someone clicks a button. Lambda expressions enable you to do this, to treat functionality as method argument, or code as data.
