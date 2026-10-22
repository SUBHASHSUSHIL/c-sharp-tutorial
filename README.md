# C# Tutorial

A comprehensive, hands-on collection of C# programming examples covering fundamentals to advanced concepts. Each topic lives in its own file with a self-contained, runnable console program demonstrating the concept in practice.

## About

This repository is a personal learning reference for C#. Every example is a standalone console application — open the file, read the code, and run it to see the concept in action. Topics are grouped below by category.

## Topics

### Basics
- [Basic Code](Basic%20Code) — Variables, input/output, type casting
- [DataType Use](DataType%20Use) — Working with C# data types
- [Code Space](Code%20Space) — Whitespace and formatting
- [Guid](Guid) — Working with the `Guid` type

### Control Flow
- [Loop](Loop) — Looping constructs
- [Loops_Csharp](Loops_Csharp) — Additional loop examples

### Arrays
- [Single_dimensional_arrays](Single_dimensional_arrays) — Single-dimensional arrays
- [Array User Input](Array%20User%20Input) — Reading array elements from user input
- [Muilti-Dimension-Array](Muilti-Dimension-Array) — Multi-dimensional (rectangular) arrays
- [Muilti-Dimension-Array-(JAGGED ARRAY)](Muilti-Dimension-Array-%28JAGGED%20ARRAY%29) — Jagged arrays

### Methods & Functions
- [Method & Fuction](Method%20%26%20Fuction) — Defining and calling methods
- [METHOD OVERLOADING](METHOD%20OVERLOADING) — Method overloading
- [Params](Params) — The `params` keyword
- [PASS_BY_REF](PASS_BY_REF) — Pass by reference vs value
- [Extension Method](Extension%20Method) — Extending existing types
- [Operator Overloading](Operator%20Overloading) — Overloading operators

### OOP Fundamentals
- [C# Class](C%23%20Class) — Class basics
- [Class & Object](Class%20%26%20Object) — Creating objects from classes
- [Structure](Structure) — Structs vs classes
- [Properties](Properties) — Properties and accessors
- [Indexer](Indexer) — Indexers
- [Static_And_Instance_Members](Static_And_Instance_Members) — Static vs instance members
- [Namespace](Namespace) — Namespaces and organization
- [Name Allowcated](Name%20Allowcated) — Naming and allocation

### OOP Pillars
- [oops Encapsulation](oops%20Encapsulation) — Encapsulation with getters/setters
- [oops ABSTRACTION](oops%20ABSTRACTION) — Abstraction
- [oops INHERITANCE](oops%20INHERITANCE) — Inheritance
- [oops Polymorphism](oops%20Polymorphism) — Polymorphism

### Constructors
- [Constructor](Constructor) — Constructor basics
- [Constructor Overloading](Constructor%20Overloading) — Overloaded constructors
- [Constructor Inheritance](Constructor%20Inheritance) — Constructor chaining across inheritance

### Inheritance & Method Behavior
- [MULTIPLE_INHERITANCE](MULTIPLE_INHERITANCE) — Multiple inheritance via interfaces
- [Method Hiding](Method%20Hiding) — Method hiding with `new`
- [Method Hiding1](Method%20Hiding1) — Additional method hiding examples
- [METHOD OVERRIDING](METHOD%20OVERRIDING) — Method overriding with `virtual`/`override`
- [Sealed Method](Sealed%20Method) — The `sealed` keyword
- [Abstract Properties](Abstract%20Properties) — Abstract classes and properties

### Interfaces
- [INTERFACES](INTERFACES) — Interface basics
- [INTERFACES_INHERITANCE](INTERFACES_INHERITANCE) — Interface inheritance
- [Explicit Implementation Of Interface](Explicit%20Implementation%20Of%20Interface) — Explicit interface implementation
- [SIMILARITIES_ABSTRACT_CLASS_INTERFACE](SIMILARITIES_ABSTRACT_CLASS_INTERFACE) — Abstract class vs interface

### Generics
- [Generic Class](Generic%20Class) — Generic classes
- [Generic Method](Generic%20Method) — Generic methods

### Collections
- [Collection ArrayList](Collection%20ArrayList) — Non-generic `ArrayList`
- [Generic & Non-Generic Collection](Generic%20%26%20Non-Generic%20Collection) — Comparing collection types
- [HashTable](HashTable) — Non-generic `Hashtable`
- [HashTable1](HashTable1) — Additional `Hashtable` examples
- [List Generic Collection](List%20Generic%20Collection) — Generic `List<T>`
- [NGQueue](NGQueue) — Non-generic `Queue`

### Delegates, Events & Lambda
- [Single_Cast_delegates](Single_Cast_delegates) — Single-cast delegates
- [THREAD_DELEGATE](THREAD_DELEGATE) — Delegates with threading
- [Anonymous Function](Anonymous%20Function) — Anonymous methods
- [Lambda Expression](Lambda%20Expression) — Lambda expressions

### Exception Handling
- [Exception Handling](Exception%20Handling) — Exception handling basics
- [Exception Demo](Exception%20Demo) — Exception demonstrations
- [Try,Catch & Finally Block](Try%2CCatch%20%26%20Finally%20Block) — try/catch/finally
- [Try With Multiple Catch Blocks](Try%20With%20Multiple%20Catch%20Blocks) — Multiple catch blocks
- [Throw Keyword And Ways Of Exception](Throw%20Keyword%20And%20Ways%20Of%20Exception) — The `throw` keyword
- [Namespace_ThrowKeywordAndWaysOfException](Namespace_ThrowKeywordAndWaysOfException) — Throw with namespaces
- [Handaling Null Reference Exception](Handaling%20Null%20Reference%20Exception) — NullReferenceException handling
- [Handling Formate Exception](Handling%20Formate%20Exception) — FormatException handling

### File Handling
- [File Handling](File%20Handling) — Basic file I/O
- [File Stream](File%20Stream) — `FileStream` operations
- [StreamWriter](StreamWriter) — Writing to files with `StreamWriter`
- [Old File Check](Old%20File%20Check) — Checking file existence and age

### Multithreading & Async
- [Muilti-Threading](Muilti-Threading) — Multithreading basics
- [Code Execute Timing Async & Await](Code%20Execute%20Timing%20Async%20%26%20Await) — async/await and timing

### Type System
- [VALUE_TYPE_REFERENCE_TYPE](VALUE_TYPE_REFERENCE_TYPE) — Value types vs reference types
- [BOXING_UNBOXING](BOXING_UNBOXING) — Boxing and unboxing
- [Is_VS_As_keyword](Is_VS_As_keyword) — `is` vs `as` keywords
- [Null_Coalesce](Null_Coalesce) — Null-coalescing operator

### Serialization & DI
- [SERIALIZATION](SERIALIZATION) — Object serialization
- [Dependency Injection](Dependency%20Injection) — Dependency injection

### Practical Projects
- [Calculator](Calculator) — A simple calculator
- [Marksheet](Marksheet) — Mark sheet generation
- [Marksheet Full Work](Marksheet%20Full%20Work) — Extended mark sheet project
- [Project_Email](Project_Email) — Email-related project

## How to Use

1. Clone the repository
2. Open any topic file in Visual Studio, VS Code, or any C# IDE
3. Copy the contents into a new C# Console Application project, or run directly with the .NET CLI:
   ```bash
   dotnet new console -n TopicName
   # Replace Program.cs contents with the topic file's code
   dotnet run
   ```
4. Each file is self-contained — run them independently to explore the concept

## Technologies

- C# / .NET Framework / .NET Core
- Console applications

## Reference

- [Dapper with Stored Procedure Tutorial](https://projectvalley.co/dapper-with-stored-procedure-tutorials/)
   - Username: sushilthakur9792@gmail.com
   - Password: Sushil@#32189
