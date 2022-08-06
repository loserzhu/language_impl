## Language Applications Cracked Open
learn how to **recognize** computer language(just a set of valid sentences).
we'll get an architectural overview and then tour the patterns at our disposal.

### 1.1 The Big picture
break the language apps into a multistage pipeline that analyzes and manipulates an input stream.
four broad language apps categories:
* Reader
* Generator:  walks an internal data structure and emits output.
* Translator & Rewriter
* Interpreter

### 1.2 A Tour of the Patterns
road map of this 31 language apps implementation patterns.(by categories)
* **Parsing Input Sentences**: use different parsing patterns according to the complexity of language syntax.
* **Constructing Trees**: construct an IR rather than repeatedly parsing the input stream.
* **Walking Trees**
* **Figuring Out What the Input Means**
* **Interpreting Input Sentences**
* **Translating One Language to Another**

### 1.3 Dissecting a Few Applications
* **Bytecode Interpreter**: We call the instructions *bytecode* because we can represent each instruction with a unique integer code from 0..255 (a byte’s range).
* **Bug Finder**
* **C Compiler**
* **Leveraging a C Compiler to Implement C++**

### 1.4 Choosing Patterns and Assembling Applications
Most of the time, we're building tools to refactor, format, compute software metrics, find bugs, instrument, or translate to another high-level language.

two basic architectures cover the majority of language applications.

We have patterns for reading input (part I), analyzing input (part II), interpreting input (part III), and generating output (part IV).

* The most basic architecture combines lexer and parser patterns. 
* The other common architecture creates an AST from the input (via tree
construction actions in the parser) 