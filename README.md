# Libft

Libft is a custom implementation of the C standard library functions. This project is part of the 42 curriculum and aims to recreate several common functions from `libc` as well as some additional utility functions.

## Table of Contents
- [Overview](#overview)
- [Functions](#functions)
  - [Part 1 - Standard libc functions](#part-1---standard-libc-functions)
  - [Part 2 - Additional functions](#part-2---additional-functions)
  - [Bonus Part](#bonus-part)
- [Usage](#usage)

## Overview

Libft is a comprehensive C library designed to provide reusable functions, closely following the behavior of standard C library functions. It includes string manipulation, memory handling, and linked list operations. By implementing these functions from scratch, this project improves understanding of the underlying mechanisms of the C language and standard library.

## Functions

### Part 1 - Standard libc functions

The first part of `libft` consists of recreating common C library functions such as:
- **Memory functions**: `memset`, `bzero`, `memcpy`, `memccpy`, `memmove`, `memchr`, `memcmp`
- **String functions**: `strlen`, `strlcpy`, `strlcat`, `strchr`, `strrchr`, `strnstr`, `strncmp`
- **Character check and transformation functions**: `isalnum`, `isalpha`, `isascii`, `isdigit`, `isprint`, `toupper`, `tolower`
- **Conversion functions**: `atoi`

### Part 2 - Additional functions

In addition to libc functions, `libft` includes a set of custom functions useful for further manipulation of memory and strings:
- **String creation and manipulation**: `substr`, `strjoin`, `strtrim`, `split`
- **Conversion functions**: `itoa`
- **Output functions**: `putchar_fd`, `putstr_fd`, `putendl_fd`, `putnbr_fd`

### Bonus Part

The bonus part extends `libft` with a linked list implementation to handle more complex data structures:
- **Linked list functions**:
  - `lstnew` - Create a new list element.
  - `lstadd_front` - Add an element to the beginning of a list.
  - `lstadd_back` - Add an element to the end of a list.
  - `lstsize` - Return the number of elements in a list.
  - `lstlast` - Return the last element of a list.
  - `lstdelone` - Delete an element from a list.
  - `lstclear` - Clear a list by deleting all elements.
  - `lstiter` - Apply a function to each element in a list.
  - `lstmap` - Create a new list by applying a function to each element of an existing list.

## Usage

To use the library, run the following command:
```sh
git clone https://github.com/LuisMBatista/libft-bonus.git
```

To compile the library, run the following command:
```sh
make
