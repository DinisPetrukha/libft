# Libft Project

## Overview

This project is the 1th project at School 42, aiming to recreate our own library in C

### Installation

Clone the repository:

```bash
git clone git@gitlab.com:dinis-petrukha/libft.git libft
cd libft
```

Execute the Makefile:
```bash
make
```

```bash
make bonus
```

# Custom C Library Functions

This repository contains a collection of custom C library functions that mimic some of the standard functions found in common C libraries. These functions cover a variety of categories, including character manipulation, memory management, string manipulation, math operations, and linked list operations.

## Functions from <ctype.h> library

### ft_isascii
- Test for ASCII character.

### ft_isalnum
- Alphanumeric character test.

### ft_isalpha
- Alphabetic character test.

### ft_islower
- Lower-case character test.

### ft_isupper
- Upper-case character test.

### ft_isdigit
- Decimal-digit character test.

### ft_isxdigit
- Hexadecimal-digit character test.

### ft_isprint
- Printing character test (space character inclusive).

### ft_isgraph
- Printing character test (space character exclusive).

### ft_isspace
- White-space character test.

### ft_isblank
- Space or tab character test.

### ft_ispunct
- Punctuation character test.

### ft_iscntrl
- Control character test.

### ft_tolower
- Upper case to lower case letter conversion.

### ft_toupper
- Lower case to upper case letter conversion.

## Functions from <stdlib.h> library

### ft_atoi
- Convert ASCII string to integer.

### ft_atof
- Convert ASCII string to float.

### ft_calloc
- Memory allocation.

## Functions from <strings.h> library

### ft_bzero
- Write zeroes to a byte string.

### ft_memset
- Write a byte to a byte string.

### ft_memchr
- Locate byte in byte string.

### ft_memcmp
- Compare byte string.

### ft_memmove
- Copy byte string.

### ft_memcpy
- Copy memory area.

### ft_memccpy
- Copy string until character found.

## Functions from <string.h> library

### ft_strlen
- Find length of string.

### ft_strlen_2
- Find length of 2D array (i.e., splitted string).

### ft_strchr
- Locate character in string (first occurrence).

### ft_strrchr
- Locate character in string (last occurrence).

### ft_strstr
- Locate a substring in a string.

### ft_strnstr
- Locate a substring in a string (size-bounded).

### ft_strcmp
- Compare strings.

### ft_strncmp
- Compare strings (size-bounded).

### ft_strnrcmp
- Reversely compare strings (size-bounded).

### ft_strcpy
- Copy strings.

### ft_strncpy
- Copy strings (size-bounded).

### ft_strdup
- Save a copy of a string (with malloc).

### ft_strndup
- Save a copy of a string (with malloc, size-bounded).

### ft_strcat
- Concatenate strings (s2 into s1).

### ft_strncat
- Concatenate strings (s2 into s1, size-bounded).

### ft_strlcpy
- Size-bounded string copying.

### ft_strlcat
- Size-bounded string concatenation.

## Functions from <math.h> library

### ft_sqrt
- Square root function.

### ft_pow
- Power function.

## Non-standard functions

### ft_swap
- Swap value of two integers.

### ft_putchar
- Output a character to stdout.

### ft_putchar_fd
- Output a character to a given file.

### ft_putstr
- Output string to stdout.

### ft_putstr_fd
- Output string to a given file.

### ft_putendl
- Output string to stdout with a newline.

### ft_putendl_fd
- Output string to a given file with a newline.

### ft_putnbr
- Output integer to stdout.

### ft_putnbr_fd
- Output integer to a given file.

### ft_itoa
- Convert integer to ASCII string.

### ft_substr
- Extract substring from a string.

### ft_strtrim
- Trim the beginning and end of a string with specified characters.

### ft_strjoin
- Concatenate two strings into a new string (with malloc).

### ft_split
- Split a string, with a specified character as a delimiter, into an array of strings.

### ft_split_free
- Free splitted string.

### ft_strmapi
- Create a new string by modifying a string with a specified function.

### ft_ftoa_rnd
- Convert float to ASCII string.

## Linked list functions

### ft_lstnew
- Create a new list.

### ft_lstsize
- Count elements of a list.

### ft_lstlast
- Find the last element of the list.

### ft_lstadd_back
- Add a new element at the end of the list.

### ft_lstadd_front
- Add a new element at the beginning of the list.

### ft_lstdelone
- Delete an element from the list.

### ft_lstclear
- Delete a sequence of elements of the list from a starting point.

### ft_lstiter
- Apply a function to the content of all list elements.

### ft_lstmap
- Apply a function to the content of all list elements, creating a new list.

---

Feel free to explore and contribute to the project!
