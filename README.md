# Basic Topics for Programming Interviews

__Note__: 
1. This may not be an exhaustive list but might give hints and directions as to what is being expected and required. Please don’t consider this as a complete list.
2. This is not just for preparing for interviews but could be helpful in terms of learning general Cpp and Python concepts.

## Contents:
- [General Programming Concepts](#general-programming-concepts)
- [C++ Programming Concepts](#c-programming-concepts)
- [Python Programming Concepts](#python-programming-concepts)

## General Programming Concepts:
- What are high level and low level programming languages?
  - What is machine code?
  - What is byte code - related to compiler and interpreter?

- What is a compiler and interpreter?
  - Difference between the two.
  - Which languages are compiled and which are interpreted or which are both?
  - What is a linker in cpp (cpp specific)?
- What is the difference between strongly typed and weakly typed languages
  - Examples.
- What is the difference between dynamic typing and static typing (related to data types).
  - Examples.
- What is OOP - Object Oriented Programming
  - Features of OOP: Encapsulation, Polymorphism, etc.
  - Implementation of OOPs in C++.
  - Implementation of OOPs in Python.
- Data Structures - Brief Overview: What is what.
  - list, vector, map, set, stack, queue, pair - C++
  - list, tuple, dict, set, stack, queue, heap - Python
  - dequeue, circular queue, priority queue
  - linked list, trees, BST
  - graphs, adjacency list, adjacency matrix
- Concurrency
  - Multithreading
  - Parallelism
  - What are processes and threads
  - What is a race condition
  - What is a deadlock
  - What is a lock
  - How to avoid race conditions
  - Multithreading in Python (Python is single threaded.. When and Why?)
  - Global Interpreter Lock (GIL)
- Memory Management
  - Stack and Heap
  - Garbage Collection (GC)
  - GC in Cpp: We need to explicitly free/deallocate memory
  - GC in Python: happens on its own but how? Just a brief idea.
- Basic Object Oriented Design (OOD) Patterns:
  - SOLID Principles
  - Singleton Design Pattern
  - Factory Design Pattern
  - Strategy Design Pattern
  

## C++ Programming Concepts:
- Pointers:
  - raw pointers,
  - smart pointers,
  - function pointers,
  - `const` with pointers.
- References:
  - What are references
  - differences between pointers and references,
  - when to use what,
  - l-value references,
  - r-value references,
- Memory management with pointers and references - stack and heap.
- call by value and reference - when to use what
- returning a pointer and/or a reference from a function/method
- `const` keyword and `const correctness` - basic understanding
- Size of data types and pointer variable, reference variable,
- lambda functions,
- use of `static` method and variable - when to use and when not to.
- `virtual` keyword and v-table.
- Inheritance:
  - Multiple Inheritance -  (advantages/disadvantages) - when would you prefer having multiple inheritance in your design?
- Polymorphism:
  - Overloading:
    - function overloading,
    - operator overloading.
  - Overriding:
    - v-table, virtual function, pure virtual functions
    - lambda functions - HOW can you achieve a similar behavior using lambda functions? Think…
- Rule 0,3,5
  - Destructors,
  - Copy constructors,
  - Copy assignment operator,
  - Move constructors,
  - Move assignment operator,
  - Which one is going to be called when (if implemented, if not implemented).
- Templates in Cpp (basic overview).


## Python Programming Concepts:
Python is all about working with different libraries. But sometimes it is still important to understand some basic concepts that might be helpful in understanding those libraries or to implement similar stuff.
- Iterators.
- Generators - yield vs return.
- Decorators.
- Comprehension (list, set, etc).
- Lambda functions.
- dunder methods (the ones with double underscore `__init__()`, `__new__()`, `__call__()`, `__iter__()`, etc.): what are they, when to use, how to use them.
- Object referencing, memory management - ‘coz everything in Python is an OBJECT!
- Immutable objects - what are they, examples, why are they made immutable.
- Modules and package structures.



