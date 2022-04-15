0x11. C - printf
================

*   By Julien Barbier, co-founder & CEO
*   Weight: 5
*   Project to be done in teams of 2 people (your team: Bamlak Desalgn, Biniyam Estifanos
*   Ongoing project - started
    
    Apr 15, 2022
    
    , must end by
    
    Apr 20, 2022
    
    \- you're done with 0% of tasks.
*   Checker will be released at
    
    Apr 16, 2022 12:00 PM
    
*   **Manual QA review must be done** (request it when you are done with the project)
*   An auto review will be launched at the deadline

Concepts
--------

_For this project, students are expected to look at these concepts:_

*   [Group Projects](/concepts/111)
*   [Pair Programming - How To](/concepts/121)
*   [Flowcharts](/concepts/130)
*   [Technical Writing](/concepts/225)

Background Context
------------------

Write your own `printf` function.

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/228/printf.png)

_^ In this picture, [Kris](/rltoken/pSPZEmqi5O8ZoeLM5-65WA "Kris"), and [Jul](/rltoken/X_vDffLlUpbtqnubfnQx8Q "Jul")_

Resources
---------

**Read or watch**:

*   [Secrets of printf](/rltoken/gxdsTXxWMklkBTgY197HYQ "Secrets of printf")
*   **Group Projects** concept page (_Don’t forget to read this_)
*   **Flowcharts** concept page

**man or help**:

*   `printf (3)`

Requirements
------------

### General

*   Allowed editors: `vi`, `vim`, `emacs`
*   All your files will be compiled on Ubuntu 20.04 LTS using `gcc`, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
*   All your files should end with a new line
*   A `README.md` file, at the root of the folder of the project is mandatory
*   Your code should use the `Betty` style. It will be checked using [betty-style.pl](https://github.com/holbertonschool/Betty/blob/master/betty-style.pl "betty-style.pl") and [betty-doc.pl](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl "betty-doc.pl")
*   You are not allowed to use global variables
*   No more than 5 functions per file
*   In the following examples, the `main.c` files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own `main.c` files at compilation. Our `main.c` files might be different from the one shown in the examples
*   The prototypes of all your functions should be included in your header file called `main.h`
*   Don’t forget to push your header file
*   All your header files should be include guarded
*   Note that we will not provide the `_putchar` function for this project

### GitHub

**There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.**

More Info
---------

### Authorized functions and macros

*   `write` (`man 2 write`)
*   `malloc` (`man 3 malloc`)
*   `free` (`man 3 free`)
*   `va_start` (`man 3 va_start`)
*   `va_end` (`man 3 va_end`)
*   `va_copy` (`man 3 va_copy`)
*   `va_arg` (`man 3 va_arg`)

### Compilation

*   Your code will be compiled this way:

    $ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
    

*   As a consequence, be careful not to push any c file containing a `main` function in the root directory of your project (you could have a `test` folder containing all your tests files including `main` functions)
*   Our main files will include your main header file (`main.h`): `#include main.h`
*   You might want to look at the gcc flag `-Wno-format` when testing with your `_printf` and the standard `printf`. Example of test file that you could 
