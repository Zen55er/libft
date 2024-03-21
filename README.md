## What is it?
A library with several (replicated) basic C functions.

## How to use this?
1 - Clone this repository

2 - Include in your project
```C
#include "<PATH>/libft.h"
```

3 - Add in makefile compilation rule (or simply in the console)
```C
$(CC) $(CFLAGS) $(YOUR_SRCS) $(<PATH>/libft.a)
```

## List of functions
| <!-- -->    | <!-- -->    | <!-- -->        |  <!-- -->      |
|-------------|-------------|-----------------|----------------|
| `isalpha` | `memmove` | `memcmp` | `ft_itoa` |
| `isdigit` | `strlcpy` | `strnstr` | `ft_strmapi` |
| `isalnum` | `strlcat` | `atoi` | `ft_striteri` |
| `isascii` | `toupper` | `calloc` | `ft_putchar_fd` |
| `isprint` | `tolower` | `strdup` | `ft_putstr_fd` |
| `strlen` | `strchr` | `ft_substr` | `ft_putendl_fd` |
| `memset` | `strrchr` | `ft_strjoin` | `ft_putnbr_fd` |
| `bzero` | `strncmp` | `ft_strtrim` |  |
| `memcpy` | `memchr` | `ft_split` |  |


## Bonus functions (for working with linked lists)

| <!-- --> | <!-- --> | <!-- --> |
|----------|----------|----------|
| `ft_lstnew` | `ft_lstlast` | `ft_lstclear` |
| `ft_lstadd_front` | `ft_lstadd_back` | `ft_lstiter` |
| `ft_lstsize` | `ft_lstdelone` | `ft_lstmap` |
