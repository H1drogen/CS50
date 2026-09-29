# CS50 Introduction

This repository contains C programs completed as part of Harvard's CS50: Introduction to Computer Science course. The exercises focus on core programming concepts such as variables, conditionals, loops, arrays, strings, and algorithm design.

## Prerequisites

- A C compiler
- CMake (version 3.28+ is specified in the project configuration)
- The CS50 library (`cs50.h`) if you are compiling course assignments that use the Harvard CS50 framework

If you are working in the official CS50 environment, the library is typically available automatically. Outside that environment, you may need to install or provide the necessary headers and runtime support.

## Building the project

From the repository root:

```bash
cmake -S . -B build
cmake --build build
```

This project currently includes a subset of the assignments in `CMakeLists.txt` by default. The entries for other exercises are commented out and can be enabled by uncommenting the relevant source file before building.

## Running a program

After building, run the generated executable from the build directory:

```bash
./build/CS50_Introduction
```

Because this repository contains multiple standalone programs, you may also compile individual C files directly if you want to test a specific exercise without building the whole project.

## Notes

- This is an educational repository for learning C and CS50 problem-solving techniques.
- Some assignments rely on Harvard's CS50 helper library and course-specific conventions.
- The project is intended as a local practice workspace rather than a production application.

## Resources

- Harvard CS50: https://cs50.harvard.edu/x/
- CMake documentation: https://cmake.org/documentation/

