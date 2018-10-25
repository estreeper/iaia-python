Syllabus
========

### Thursday, October 18th 2018

## Introduction

A little command line
 * the terminal: opening it and reading it
 * how spaces are used to separate arguments
 * change directories: `cd`
 * list directory contents: `ls`
 * directory shortcuts: `~`, `.` and `..`
 * where am I? print working directory: `pwd`
 * make and remove files: `touch` and `rm`
 * make and remove directories: `mkdir` and `rmdir`
 * running python: interactive mode (REPL) vs. executing a .py file

Python Basics
 * ints/floats
 * math operations: `+`, `-`, `*`, `/`, `**`, `%`
 * strings
 * errors are good: line numbers, understanding them
 * variables and assignment
 * builtins: `print`, `input`
 * equality operators: `==`, `!=`, `>`, `<`, `>=`, `<=`
 * booleans: `True`, `False`
 * Using `and` and `or`
 * if statements: `if`, `elif`, `else`

Discussion: formatting and style. Snake case. The importance of indentation and
how it's different from other languages. PEP 8. A Foolish Consistency is the
Hobgoblin of Little Minds.

## First project: talk to the machine.

Using `input`, `if` statements, and `print`, write a program that asks a
question and reacts to the response. Then, let your neighbor try your program.

### Thursday, October 25th 2018

## Digging in

Recap and stuff we missed
 * moving files: the `mv` command
 * the DRY principle
 * making things more robust

A little more Python
 * functions: `def` keyword, positional arguments, keyword arguments, `return`
 * data structures: lists, tuples
 * looping: `for` with lists and `range`
 * list operations: list indexes, `len`, `append`, `pop`
 * using the `import` statement
 * using `random` with `randint` and `choice`

## Getting started with packages: Pillow

Package managers and virtual environments
 * extending functionality with packages
 * first package: pip, the better package manager
 * second package: virtualenv
 * using virtual environments to isolate projects
 * our first fun package: Pillow for image manipulation

Playing with images in programs
 * the `import` statement
 * the `Image` class
 * the `dir` function
 * getting the image with `Image.open`
 * saving an image to a new format with `Image.save`
 * pasting images with `paste`
 * using `crop` to get a rectangle
 * using `transpose`
