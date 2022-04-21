**printf**

This is the first group project for done by **Christian Anichebe and Ogbodo Ogonna for ALX Software Engineering program**, which involves

replicating a formatted output conversion for standard C program printf and calling it as **_printf.**

**Dependencies**

The _printf function was coded on an Ubuntu 20.04 LTS machine with gcc version 11.2.

**Parameters Used**

The following format types was chosen for this project:

**Type	       Output	                         Example**

**C**	          Character	                       **A**

**s**     	String of characters	                  **ALX**

**%**	This will write a single % to the stream	    **%**

**i** and d	Signed decimal integer	               **98**

**b**	Unsigned binary	                         **10101**

**u**	Unsigned decimal integer	                 **98**

**o**	Unsigned octal	                            **5523**

**x**	Unsigned hexadecimal integer (lowercase)	**36264ad**

**X**	Unsigned hexadecimal integer (uppercase)	**37854AB**

**r**	Reserved string	                       **gnirts**

**R**	Rot13 string	                            **cevags**

**Description**

This is a formatted output of the standard printf function in C. Our project required a function capable of printing with the %d, %c,

%s, and %% specifiers to standard output. _printf returns the number of characters printed (excluding the null byte at the end of

strings). We were not asked to handle flag characters, field width, precision, or length.

**How to use**

All of the .c files along with a main.c file are to be compiled with gcc 11.2 on Ubuntu 20.04 LTS with the flags below:

$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c

**Contributors**

Christian Anichebe Christianobinna71@gmail.com

Ogbodo Ogbonna ogbodojoseph62@gmail.com


**Acknowledgments**

The _printf function emulates functionality of the C standard library function printf. This README is curated from the Linux man page

**printf(3)**
