# CPP-Modules

> [!IMPORTANT]
> None of my code is publicly available here, but if you're a recruiter, I'd be happy to share it with you upon request.

<p align="center"> 
  <img width="397" height="533" alt="Screenshot from 2025-07-24 10-52-05" src="https://github.com/user-attachments/assets/01363ad7-9e2e-4d21-b701-b14d958192c6" />
</p>

## C++ Module 00 – Basics of Object-Oriented Programming
The Module 00 was my entry point into the world of C++. It focused on understanding the foundations of Object-Oriented Programming (OOP) and how C++ builds upon C with new syntax and paradigms.

What I had to do:
* Create basic classes and instantiate objects
* Understand and use member functions, attributes, and access specifiers
* Learn about namespaces, header files, and source files for code organization
* Handle static members and their implications
* Apply pointers to members and their correct syntax

What I Learned:
* The C++ class structure and how to encapsulate behavior and state
* Differences between **public**, **private**, and **protected**
* How to split code into `.hpp` and `.cpp` files using proper includes
* Why static members can be useful for class-wide logic or state
* C++ conventions for memory layout, object lifecycle, and function declarations

## C++ Module 01 – Memory and References
This module dove deeper into memory management, references, and class construction mechanics.

What I had to do:
* Implement constructors, destructors, and the **canonical class form**
* Use reference variables and understand their differences from pointers
* Handle initialization lists in constructors
* Work with heap vs stack allocation
* Understand copy constructors and assignment operators

What I Learned:
* The importance of managing object lifetime properly
* Differences between shallow and deep copying
* Best practices when dealing with dynamic memory
* How references help write cleaner, safer C++ code

## C++ Module 02 – Polymorphism and Operator Overloading
This module introduced operator overloading and explored how to use overloads to implement intuitive behavior in classes.

What I had to do:
* Overload **arithmetic**, **comparison**, and **stream operators**
* Implement increment/decrement operators
* Create a class that simulates fixed-point arithmetic
* Handle **rounding**, **comparison**, and **precision control**

Bonus Part:
* Implement `min`/`max` static methods to compare instances
* Add robust test cases to evaluate all operator behaviors

What I Learned:
* How C++ allows intuitive syntax via operator overloading
* Writing clean, expressive APIs for custom types
* Managing internal representation while exposing high-level behavior
* Handling arithmetic precision and floating-point quirks

## C++ Module 03 – Inheritance and Abstract Design
Module 03 introduced inheritance, protected access, and hierarchical design in C++.

What I had to do:
* Create a base class and derive multiple child classes
* Use virtual destructors to prevent memory leaks in **polymorphic** usage
* Apply **constructors/destructors** in **inheritance** chains
* Implement attack and damage simulation via character classes

Bonus Part:
* Implement FragTrap and ScavTrap classes with unique behavior
* Add logging and status effects to make inheritance more dynamic

What I Learned:
* The power of inheritance to promote code reuse and abstraction
* Proper use of protected members for child class access
* Why virtual destructors are essential for safe polymorphism
* How to separate shared vs specific behavior in a class hierarchy

## C++ Module 04 – Polymorphism and Interface Abstraction
* This module focused on runtime polymorphism, abstract classes, and deep copying of resource-managed classes.

What I had to do:
* Define an abstract Animal base class with a pure virtual function
* Derive Cat and Dog classes implementing the `makeSound()` method
* Add a Brain class dynamically allocated inside animals
* Handle **deep copying** to avoid shared state between instances

Bonus Part:
* Add logging, internal state tracking, and manual testing
* Implement a custom memory leak detector or use tools like valgrind

What I Learned:
* How to design safe and effective abstract interfaces
* Managing deep vs shallow copies in polymorphic classes
* The need for the Rule of Three/Five when working with heap-allocated members
* Runtime **polymorphism** through base class pointers and references

## C++ Module 05 – Exceptions and Error Handling
Focused on the proper use of exceptions in C++ as an error-handling mechanism.

What I had to do:
* Throw and **catch exceptions** using `try` / `catch`
* Create custom exception classes derived from `std::exception`
* Apply exception safety in constructors and critical operations
* Design a grade-based bureaucratic system:
* Bureaucrat class with `signForm()` logic
* Form class that throws exceptions on invalid grades

What I Learned:
* Robust error handling with meaningful messages
* Proper inheritance and polymorphism for exceptions
* Writing exception-safe constructors and methods
* How to enforce rules through exception-based control flow

## C++ Module 06 – Type Conversion and Scalar Conversion
This module tackled type casting, conversions, and edge-case handling in scalar types.

What I had to do:
* Parse a single input argument and attempt to display its value as:
  * `char`, `int`, `float`, and `double`
* Handle invalid inputs, precision control, and special values like `nan`, `inf`, etc.
* Implement detection for pseudo-literals
* Extend support to edge cases like:
  * Overflowing values
  * Non-displayable characters
  * Tricky type ambiguities

What I Learned:
* How to parse and validate user input in a type-safe way
* Proper type **casting** strategies and when to use each C++ cast
* Working with floating-point edge cases and limits
* Error handling and reporting in type-sensitive programs

## C++ Module 07 – Templates and Generic Programming
This module explored function and class templates, allowing for flexible and reusable code.

What I had to do:
* Implement a function **template** (`swap`, `min`, `max`)
* Create a custom `Array<T>` class to mimic a fixed-size array
* Handle element access, size tracking, and out-of-bounds errors
* Add bounds-checking with exceptions
* Implement a copy constructor and assignment operator to allow safe copying
* Write detailed tests to demonstrate **template versatility**

What I Learned:
* How to write generic, type-agnostic code in C++
* Ensuring exception safety and clean copy semantics
* The complexity of writing reusable and reliable templated containers
* C++ templates as a compile-time polymorphism tool

## C++ Module 08 – Containers and Iterators
This module focused on standard containers, iterators, and managing collections of polymorphic objects.

What I had to do:
* Use `std::vector`, `std::list`, and other **STL containers**
* Iterate over containers using classic and STL iterators
* Implement a simulation with polymorphic types stored in a container
* Implement the MutantStack:
  * A custom **stack container** that exposes iterators like a list
  * Reuses `std::stack` as a base and provides range-based support
  * Write custom test cases demonstrating stack traversal and modification

What I Learned:
* Power and flexibility of **STL containers**
* **Iterator** categories and how they apply to different containers
* How to extend standard containers for new functionality
* Cleanly managing object lifetimes and memory in containers of polymorphic types

## C++ Module 09 – Algorithms, Performance, and Pseudo-Containers
The final module explored algorithm design, performance benchmarking, and hybrid sorting techniques.

What I had to do:
* Implement a program to sort integers using a merge-insert hybrid algorithm
* Work with both `std::deque` and `std::vector` as underlying containers
* Validate input, handle duplicates, and enforce numeric constraints
* **Benchmark** sorting time for both containers
* Display sorting durations in microseconds
* Optimize and analyze algorithmic complexity for small vs large data sets

What I Learned:
* Performance trade-offs between different STL containers
* How to write hybrid algorithms that adapt to input size
* Practical use of chrono timing functions and benchmarking
* Handling input parsing, sanitization, and validation robustly

## Final Thoughts
The C++ Modules 00–09 — with all bonuses completed — offered a rich, progressive journey into modern C++ development. They built up from the very basics to advanced language features, focusing on clean design, performance, and safe memory management. The bonus parts helped me push each concept further, from inheritance chains to custom containers, benchmarking, and even runtime polymorphism.

What I took away from this journey:
* Deep understanding of C++ OOP, templates, casting, and exceptions
* Confidence working with containers, iterators, and custom class hierarchies
* Ability to write performant, reusable, and scalable C++ code
* A solid foundation for tackling real-world system programming, performance-critical apps, or complex architectural designs

These modules are not just academic — they simulate the depth and complexity of professional-grade C++ development and gave me hands-on experience with some of the most powerful features of the language.
