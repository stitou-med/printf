# printf Project
## General

    Allowed editors: vi, vim, emacs
    All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
    All your files should end with a new line
    A README.md file, at the root of the folder of the project is mandatory
    Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
    You are not allowed to use global variables
    No more than 5 functions per file
    In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
    The prototypes of all your functions should be included in your header file called main.h
    Don’t forget to push your header file
    All your header files should be include guarded
    Note that we will not provide the _putchar function for this project

# Tasks

These are all the tasks of this project, the ones that are completed link to the corresponding files.

### [0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life]
* Write a function that produces output according to a format.

    Prototype: int _printf(const char *format, ...);
    Returns: the number of characters printed (excluding the null byte used to end output to strings)
    write output to stdout, the standard output stream
    format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
        c
        s
        %
    You don’t have to reproduce the buffer handling of the C library printf function
    You don’t have to handle the flag characters
    You don’t have to handle field width
    You don’t have to handle precision
    You don’t have to handle the length modifiers


### [1. Education is when you read the fine print. Experience is what you get if you don't](handle_print.c)
* Handle the following conversion specifiers:

    * d
    * i
    You don’t have to handle the flag characters
    You don’t have to handle field width
    You don’t have to handle precision
    You don’t have to handle the length modifiers


### [2. Just because it's in print doesn't mean it's the gospel]()
* Create a man page for your function

### [3. With a face like mine, I do better in print]()
* Handle the following conversion specifiers:
  - b : the unsigned int argument is converted to binary

### [4. What one has not experienced, one will never understand in print]()
* Handle the following conversion specifiers:
  - u : converts the input into an unsigned integer
  - o : converts the input into an octal number
  - x : converts the input into a hexadecimal number
  - X : converts the input into a hexadecimal number with capital letters

### [5. Nothing in fine print is ever good news]()
* Use a local buffer of 1024 chars in order to call write as little as possible.

### [6. My weakness is wearing too much leopard print](./print_custom.c)
* Handle the following custom conversion specifier:
  - S : prints the string
  - Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

### [7. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print](./print_address.c)
* Handle the following conversion specifier:
  - p : int input is converted to a pointer address

### [8. The big print gives and the small print takes away](./get_flag.c)
* Handle the following flag characters for non-custom conversion specifiers:
  - \+ : adds a \+ in front of signed positive numbers and a \- in front of signed negative numbers
  - space : same as \+, but adds a space (is overwritten by \+)
  - \# : adds a 0 in front of octal conversions that don't begin with one, and a 0x or 0X for x or X conversions

### [9. Sarcasm is lost in print]
* Handle the following length modifiers for non-custom conversion specifiers:
  - l : converts d, i, u, o, x, X conversions in short signed or unsigned ints
  - h : converts d, i, u, o, x, X conversions in long signed or unsigned ints

### [10. Print some money and give it to us for the rain forests]
* Handle the field width for non-custom conversion specifiers.

### [11. The negative is the equivalent of the composer's score, and the print the performance]
* Handle the precision for non-custom conversion specifiers.

### [12. It's depressing when you're still around and your albums are out of print]
* Handle the 0 flag character for non-custom conversion specifiers.

### [13. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection]
* Handle the - flag character for non-custom conversion specifiers.

### [14. Print is the sharpest and the strongest weapon of our party](./print_custom.c)
* Handle the following custom conversion specifier:
  - r : prints the reversed string

### [15. The flood of print has turned reading into a process of gulping rather than savoring](./print_custom.c)
* Handle the following custom conversion specifier:
  - R : prints the rot13'ed string

### [16. * ]
* All the above options work well together.

---

### Authors
* **STITOU MOHAMED** - [stitouu09@gmail.com](https://github.com/stitou-med)
