---
title: C
logo: c

wikipedia_excerpt: |
  C is a general-purpose, procedural computer programming language supporting structured programming, lexical variable scope, and recursion, while a static type system prevents unintended operations

key_links:
  wikipedia: https://en.wikipedia.org/wiki/C_(programming_language)
links:
  - title: The Development of the C Language
    url: https://www.bell-labs.com/usr/dmr/www/chist.html
    description: Article on the Bell Labs site.

tutorials:
  - title: What is C Programming Language? Basics, Introduction and History
    url: https://www.guru99.com/c-programming-language.html
  - title: C language introduction
    url: https://www.geeksforgeeks.org/c-language-set-1-introduction/
  - title: C in 100 seconds
    url: https://youtu.be/U3aXWizDbQ4
---


<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/The_C_Programming_Language_logo.svg" width="100" />


### Overview

- _C_ is a general-purpose language.
- History
    - Started in 1972.
    - C was intended for Unix systems initially, but now most languages and operating systems use it.
    - Influenced by [B](https://en.wikipedia.org/wiki/B_(programming_language)), which in turn was influenced by [BCPL](https://en.wikipedia.org/wiki/BCPL)
- It is known for its high performance and control of low-level areas such as managing memory.
- _C_ is not so beginner-friendly - you need verbose code compared with other languages, even to do something simple. Some alternatives are C++ or Java, or the more modern Go and Rust.
- However, the advantage is that gives a high degree of control which means you can optimize memory management at a low-level.
- Strongly and statically typed. You have to explicitly set the type (e.g. 32-bit signed integer) in most cases and objects cannot change type. The types are checked at compile time.
- You compile your scripts into binary executables specific to an OS. This makes it very portable - if a compiled binary is produced for each of Linux, Windows, and macOS, they can be distributed online and downloaded and run by anyone.
- By having the compile step, there is an initial cost in time. But then the compiled code can run much faster later than interpreted code such as in JavaScript, Ruby or Python.
- C has variables and functions.
- Memory is managed manually. There js no garbage collection. This gives more control for systems programming.
- There are no classes. There is no string type (though you can have an array of characters). There is no boolean - instead you use `0` for false and `1` for true.
- It makes use of pointers - a function can operate on a pointer of a variable and modify it in place, without making a copy of the value which would use extra memory.
- Extensions:
    - `.c` - source code file.
    - `.h` - header file. It may contain constants, function prototypes and external variable definitions.
    - `.o` - compiled object file.
    - `.so` - shared object file.


### Implementation

Most programming language you come across such as Bash, Python or Java will be **implemented** in _C_.

For example, the commonly used version of Python known as CPython and can be found here GitHub as ([python/cpython](https://github.com/python/cpython)). That is Python implemented in _C_. You will see many files there written in _C_ with `.c` or `.h` extensions. When you run Python code or import a builtin library, you might be running compiled _C_ code directory or you might be running _Python_ code which internally runs _C_ code. Running _C_ directly is typically much faster, as running Python code requires interpretation and compilation at runtime.

There are alternatives such as _Jython_ implemented in Java and _IronPython_ implemented in C#.


### Help

Get help on the GNU C Compiler

```sh
$ man cc
$ info cc
$ cc --help
```

See also:

```sh
$ gcc
```

For C++ and C code:

```sh
$ g++
```
