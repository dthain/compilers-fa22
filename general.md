# General Submission Instructions

## Build Environment

To ensure a consistent environment between development and grading,
please use the standard CSE student machines (RHEL8) to build and test your code.
These machines are using gcc-8.5.0, flex-2.6.1, and bison-3.0.4.
Use `which gcc` to double check that you are using the standard `/usr/bin/gcc`
and have not otherwise modified your PATH for another class.

## Code Organization

To ensure that you get off on the right fit (and we are able to understand your code)
you will be required to use the standard [starter code](http://github.com/dthain/compilerbook-examples)
which defines structures like `decl`, `expr` and so forth.  You are welcome to add files,
fields, and functions as you like, as long as the general purpose of these structures remains.

Your code must include a `Makefile` such that when you type `make`, the entire compiler (so far)
is built and produces a program called `bminor`. Each assignment page will specify what arguments are required to call it.
Likewise, `make clean` should remove all intermediate object files, automatically generated code, and so forth.

## Getting Started with Git

## Turning In Code to Github



