# Libft

Libft is a custom C library developed

The goal of this project is to recreate a collection of commonly used functions from the C standard library and implement additional utility functions.

## Project Structure

```text
libft/
├── Makefile
├── libft.h
├── ft_atoi.c
├── ft_bzero.c
├── ft_calloc.c
├── ft_isalnum.c
├── ft_isalpha.c
├── ft_isascii.c
├── ft_isdigit.c
├── ft_isprint.c
├── ft_memcpy.c
├── ft_memset.c
├── ft_putchar_fd.c
├── ft_putendl_fd.c
├── ft_putnbr_fd.c
├── ft_putstr_fd.c
├── ft_strchr.c
├── ft_strdup.c
├── ft_strlcat.c
├── ft_strlcpy.c
├── ft_strlen.c
├── ft_strncmp.c
├── ft_strnstr.c
├── ft_strrchr.c
├── ft_tolower.c
└── ft_toupper.c
```

## Functions

### Character Functions

* `ft_isalpha`
* `ft_isdigit`
* `ft_isalnum`
* `ft_isascii`
* `ft_isprint`
* `ft_toupper`
* `ft_tolower`

### String Functions

* `ft_strlen`
* `ft_strchr`
* `ft_strrchr`
* `ft_strncmp`
* `ft_strnstr`
* `ft_strdup`
* `ft_strlcpy`
* `ft_strlcat`

### Memory Functions

* `ft_memset`
* `ft_bzero`
* `ft_memcpy`
* `ft_calloc`

### Conversion

* `ft_atoi`

### File Descriptor Functions

* `ft_putchar_fd`
* `ft_putstr_fd`
* `ft_putendl_fd`
* `ft_putnbr_fd`

## Compilation

The project uses a `Makefile`.

Build the library:

```bash
make
```

Clean object files:

```bash
make clean
```

Remove object files and the library:

```bash
make fclean
```

Rebuild everything:

```bash
make re
```

## Usage

Include the header:

```c
#include "libft.h"
```

Compile your program with the library:

```bash
cc main.c libft.a -o program
```

Then run:

```bash
./program
```

## Compiler Flags

The project is compiled using:

```text
-Wall -Wextra -Werror
```
