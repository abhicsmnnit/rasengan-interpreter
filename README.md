# Rasengan Interpreter
This is an interpreter for a language named Rasengan.

It's pretty heavily influenced by the book `Writing an Interpreter in Go` by `Thorsten Ball`.

## Features
It's meant to supports the following features:
* C-like syntax
* variable bindings
* integers and booleans
* arithmetic expressions
* built-in functions
* first-class and higher-order functions
* closures
* a string data structure
* an array data structure
* a hash data structure

### Code examples
```Java
// Variable bindings
let name = "Naruto Uzumaki";
let age = 16;
let isNinja = true;
let result = 10 * (20 / 2);

// Integer array
let bijuTailCounts = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

// Hash
let naruto = {"name": "Naruto Uzumaki", "age": 16};

// Accessing the elements of an array and hash using the index operator
bijuTailCounts[8] // => 9
naruto["name"] // => "Naruto Uzumaki"

// Functions
let add = fn(a, b) { return a + b; };
let mul = fn(a, b) { a * b; }; // Implicit return value

// Calling a function
add(5, 10);
```