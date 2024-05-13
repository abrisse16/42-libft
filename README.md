<div align=center>

# <b>Libft</b>

### 42 common core / circle #0
<i>This project is my very first project as a student at 42. I had to recode several functions of the C standard library as well as other utility functions that I will use throughout my entire cursus.</i>

##

### Final grade
[![abrisse's 42 Libft Score](https://badge.nimon.fr/api/v2/clw51aj8x026501rzp5ef4x2f/project/2416160)](https://github.com/Nimon77/badge42)

### Subject
English version [here](https://github.com/abrisse16/42-subjects/blob/7385a594afd19b06ab40ed62b5e8c818d2d8bd21/libft-subject-v15.en.pdf)
<br>
French version [here](https://github.com/abrisse16/42-subjects/blob/7385a594afd19b06ab40ed62b5e8c818d2d8bd21/libft-subject-v15.fr.pdf)

</div>

---

## The project

In this project, we must re-code a set of useful functions. The functions will be added to a library called <i>libft.a</i> that we will be able to reuse in all our projects.

<br>

The first set of functions are functions that we already know from the C standard library. The functions will need to have the same prototype and behave in the same way as the originals, as defined in their man. The functions' names must be prefixed by <i>ft_</i>.

<p align=center>
isalpha
• isdigit
• isalnum
• isascii
• isprint
• strlen
• memset
• bzero
• memcpy
• memmove
• strlcpy
• strlcat
• toupper
• tolower
• strchr
• strrchr
• strncmp
• memchr
• memcmp
• strnstr
• atoi
</p>

<br>

The second set of functions are functions that are either not included in the C standard library, or included in a different form.

<p align=center>
substr
• strjoin
• strtrim
• split
• itoa
• strmapi
• striteri
• putchar_fd
• putstr_fd
• putendl_fd
• putnbr_fd
</p>

<br>

The bonus set of functions are functions that are not mandatory. These functions allow us to easily manipulate linked lists.

<p align=center>
lstnew
• lstadd_front
• lstsize
• lstlast
• lstadd_back
• lstdelone
• lstclear
• lstiter
• lstmap
</p>

## Usage

Clone this repository :

```sh
git clone https://github.com/abrisse16/42-libft.git path/to/repository
```

In your local repository, run `make`

To use the library in your project, include the header file `libft.h` located in the `includes` directory.

```c
#include "libft.h"
```

Then, compile your project with the library :

```sh
[...] -L path/to/libft.a -lft -I path/to/libft.h
```

---
<div align=center>
	<a href="mailto:abrisse@student.42.fr">abrisse@student.42.fr</a>
</div>