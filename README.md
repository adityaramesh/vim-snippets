# Introduction

This repository is a fork of [this one](https://github.com/honza/vim-snippets),
which is maintained [honza](https://github.com/honza). All existing snippets
have been moved to the `reference` directory. I refer to the existing snippet
files when I write my own for the languages that I use most frequently.
Questions, comments, and pull requests are welcome.

# C++

The snippet file for C++ is intended for development using the C++1y standard.
There is an emphasis on modern C++ style and programming idioms. Snippets are
provided for preprocessor directives, conditional statements, loops, and
templates. Currently, five types of for loops are supported:

- The common for loop with integer induction variable in the range `[0, count]`.
- A for loop whose induction variable is an iterator over a container. 
- A range-for loop over the elements of a container.
- A range-for loop over an explicit list of elements.
- A foreach loop implemented using `std::for_each`.
