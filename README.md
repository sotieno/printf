# Secrets of printf in C

![](https://blog.vantagecircle.com/content/images/size/w1000/2020/08/teamwork-and-team-building.png)

---

In this project, we unlock the secrets of printf while working in collaboration on GitHub to create a custom printf function.

---

## What is the printf function:

**Description**
:----
printf is the C language function to do formatted printing and from this project we learn how it works and how to design the proper formatting specification for any occasion. This function write its output to the stdout (standard output) and returns the count of printed characters when the function is successful. The available convertion specifiers are:

* %c: Prints a single character.
* %s: Prints a string of characters.
* %d: Prints integers.
* %i: Prints integers.
* %b: Prints the binary representation of an unsigned decimal.
* %u: Prints unsigned integers
* %x: Prints the hexadecial representation of an unsigned decimal in lowercase letters
* %X:Prints the hexadecial representation of an unsigned decimal in uppercase letters
* %r: Prints a reversed string

## Functions and macros in use:

**Description**

* write: allows you to communicate with other users
* malloc: allows you to allocate memory dynamically
* free: allows you to free dynamically allocated memory
* va_start: macro
* va_end: macro
* va_copy: macro
* va_arg: macro

### Compilation

**Note**

* The code is compiled using: `gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c`

* The gcc flag `-Wno-format` is used when testing your `_printf` and the standard `printf`

* The c project files include the main header file `main.h` and exclude a main function

* A test folder containing all c test files including main functions is included

**Authors**

* [majimpala](https://github.com/majimpala)
* [Sylvia Otieno](https://github.com/sotieno)

###
###
Sylvia Otieno
Aaron Mrima
