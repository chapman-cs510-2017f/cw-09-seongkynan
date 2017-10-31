# CS510 CW 9

**Author(s):** **Seong and Kynan**

[![Build Status](https://travis-ci.org/chapman-cs510-2017f/cw-09-seongkynan.svg?branch=master)](https://travis-ci.org/chapman-cs510-2017f/cw-09-seongkynan)

## Specification

**Note: Remember this is a C project.**

Complete the following exercises, saving your solutions in the indicated files. 

1. Read the following style guide carefully for C, and use it: [C Style Guide](https://en.wikibooks.org/wiki/C_Programming/Structure_and_style)
1. Use the following references as needed in what follows. They will be useful throughout the rest of the course.
    * [Learn C in Y Minutes](https://learnxinyminutes.com/docs/c/)
    * [C Cheat Sheet](https://www.cheatography.com/ashlyn-black/cheat-sheets/c-reference/)
    * [C Programming Wikibook](https://en.wikibooks.org/wiki/C_Programming)
    * [Learn Make in Y Minutes](https://learnxinyminutes.com/docs/make/)
    * The C textbook linked in the info repository.
1. Note that `.travis.yml` has changed to reflect the fact that this is a C repository.
1. Read through all the source files - there are substantial comments walking you through how C works.
1. Verify that running the command ```make test``` in a command line (from within your repository directory) compiles code and runs unit tests. Do the tests pass? Look through the code. In a Jupyter notebook ```C_Compilation.ipynb```:
    * Describe what the purpose of a Makefile is
    * Describe how the code is organized here. Why is this a reasonable structure?
    * Describe what a header file is.
    * Describe what a source file is.
    * Describe what an object file is.
    * Describe what compiling is.
    * Describe what linking is.
1. Look at the definitions for the C function ```int factorial(int n)```. In a Jupyter notebook ```Factorial.ipynb```:
    * Describe the algorithm being used.
    * Describe two problems with the current function definition.
    * Describe how you can fix those problems.
1. Edit the file ```factorial.c``` (using ```vim```) to fix the two problems you identified. Make sure the tests now pass. Are there any other subtle bugs?
1. Edit the file ```test_factorial.c``` (using ```vim```) to add one more reasonable test for the factorial function. Make sure the new test passes. 
1. Push only the changes to the header or source files to GitHub, along with your Jupyter notebooks. You should never push binary programs, or object files, or logs.
1. Make sure that Travis shows that the tests pass correctly.

## Assessment

Analyze in this section what you found useful about this assignment in your own words. Include any lingering questions or comments that you may have.

1. **Makefile is a convenient build tool to compile different sources files as desired.**
2. **Compiling language is not as convenient to use as an interpreter language like Python, because we have to compile every time when we modify source codes. But it is faster when running, because it is closer to the machine.**
3. **C language is a type language, which we need to familiar to in order to make an efficent program.**

## Honor Pledge

I pledge that all the work in this repository is my own with only the following exceptions:

* Content of starter files supplied by the instructor;
* Code borrowed from another source, documented with correct attribution in the code and summarized here.

Signed,

**Seong and Kynan**
