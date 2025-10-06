---
layout: post
---

hello. let's talk about compilers. 

### What are Compilers?

Compilers are programs that translate one form into another. For example, C++ to machine code, Typescript to Javascript (Translating from one source code to another is a special compiler called a transpiler), etc.

There is also a thing called an interpreter, which is the same process as a compiler except it doesn't produce a target language but instead directly executes the program. Some languages, like Java & Python, are hybrids and use both.

The advantage of a compiler is that it is faster because it performs optimizations, and executes effecient machine code, whie a interpreter goes back and forth between translation and execution. However, an interpreter is a lot more flexible.

### What is the architecture of a compiler?

A compiler can be distinguished into two parts: syntax analysis and ...
but to an engineer's pov, it's easier to distinguish into the frontend and backend, reason being if you wanted to change how a language looks and is used, you'd change the frontend. But if you were to create it's usability for a specific computer architecture or system, you wouldn't change the language features itself but how it is compiled to work on a specific machine, so you change the backend.

Here's the broad overview of a compiler's architecture: [drawing]
Scanner (Lexical analysis) -> Parser (Synax analysis) -> Semantic analysis -> intermediate code generation -> optimization -> target code generation

Now let's dive into each part!

### Scanner / Syntax/Lexical Analysis

Takes in the source code and spits out a stream of tokens.

A scanner scans through the source code (ik, shocker!), and turns each lexeme into a token. A lexeme is ___ and a token is a single representation of it. 
Example: [drawing]

For a token to be useful, it also needs to hold some additional information such as the literal value, it's appearance in the code, etc. This'll be used later on.

### Parser

Takes in the stream of tokens and spits out a parse tree.

What is a parse tree?

What are the different types of parse trees?

But, why?

Note: The scanner and parser usually work together immediately, as in each time a scanner produces a token it is immediately passed to the parser. It's not a sequential large operation but rather the information is passing along as it is being created.

### Semantic Analysis


