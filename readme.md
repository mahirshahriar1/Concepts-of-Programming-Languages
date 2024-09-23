# My First Language Frontend with LLVM

Welcome to the "My First Language Frontend with LLVM" project! This repository contains the implementation of a simple programming language called **Kaleidoscope**, built using LLVM. The goal of this project is to demonstrate how easy it can be to create a language frontend and generate code with LLVM.

Doc Link : 
https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/

## Overview

This project is structured into several chapters, each covering key concepts in language design and LLVM integration:

1. **Kaleidoscope Language and Lexer**: Introduces the language and implements a simple lexer.
2. **Implementing a Parser and AST**: Covers parsing techniques and Abstract Syntax Tree (AST) construction.
3. **Code Generation to LLVM IR**: Demonstrates how to generate LLVM Intermediate Representation (IR).
4. **Adding JIT and Optimizer Support**: Shows how to incorporate Just-In-Time (JIT) compilation.
5. **Extending the Language: Control Flow**: Introduces control flow operations like 'if' statements and loops.
6. **Extending the Language: User-defined Operators**: Allows users to define custom operators with assignable precedence.
7. **Extending the Language: Mutable Variables**: Adds local variable support and assignment operations.
8. **Compiling to Object Files**: Explains how to compile LLVM IR to object files.
9. **Debug Information**: Adds support for debugging features like breakpoints and function calls.
10. **Conclusion and Future Directions**: Wraps up the series and discusses potential extensions.

## Getting Started

To run and experiment with the code:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/kaleidoscope.git
   cd kaleidoscope
