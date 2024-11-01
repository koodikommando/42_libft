# Libft

A custom implementation of essential C library functions as part of the 42 curriculum. The goal of this project is to deepen understanding of C programming by building a personal library of commonly used functions that can be reused across other projects.

## **Overview**

The `libft` project replicates several standard C library functions like `strlen`, `strcpy`, `memset`, as well as some additional utility functions. This library is a foundation for future 42 projects, allowing students to work without relying on the standard C library.

## **Features**

- Re-implemented a variety of functions from `<string.h>`, `<stdlib.h>`, and `<ctype.h>`.
- Additional utility functions to support string manipulation, memory management, and linked lists.
- Organized as a static library for easy reuse in future projects.

## **Usage**

### 1. Cloning the Repository

To start, clone the repository:
```bash
git clone git@github.com:koodikommando/42_libft.git
cd libft
```

### 2. Compilation

Compile the library using the provided Makefile:
```bash
make
```

This will produce `libft.a`, a static library that can be linked to other projects.

### 3. Using Libft in Your Project

In your project, include the `libft.h` header and compile with `libft.a`:
```c
#include "libft.h"
```

Compile and link:
```bash
gcc main.c libft.a
```

## **Project Structure**

- `libft/` - Contains the implementation files for each function.
- `libft.h` - Header file with function prototypes.
- `Makefile` - For compiling the library and managing dependencies.

