## Functional Programming Concepts

### What is functional programming?
Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data.
### What is a pure function and how do we know if something is a pure function?
A pure function is a function that always produces the same output for the same input and has no side effects; we can determine it by checking if it relies only on its input parameters and doesn't modify external state.
### What are the benefits of a pure function?
The benefits of pure functions include easier testing, improved code clarity and maintainability, and support for parallel and concurrent execution.
### What is immutability?
Immutability refers to the property of an object or data structure that cannot be modified after it is created.
### What is Referential transparency?
Referential transparency means that a function's output can be replaced with its result without affecting the program's behavior.

### Node JS Tutorial for Beginners #6 - Modules and require()

### What is a module?
A module is a self-contained unit of code that encapsulates related functionality and can be imported and used in other parts of a program.
### What does the word ‘require’ do?
The word 'require' is used in Node.js to import a module and make its functionality available in the current file.
### How do we bring another module into the file the we are working in?
To bring another module into the file we are working in, we use the 'require' function followed by the module's path or name.
### What do we have to do to make a module available?
To make a module available, it needs to be installed in the project's dependencies and its import statement should be included in the file where it will be used.