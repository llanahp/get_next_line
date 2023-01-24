# get_next_line

get_next_line is a 42 project that consists of creating a function that reads a file line by line. The main objective is to learn about dynamic memory management and error handling in C, you also learn about the use of file descriptor and how to handle files in C. This project is an excellent opportunity to learn about file handling and improve skills in C programming and code optimization.

# How to use it

To use the function in your code, simply include its header:

```C
#include "get_next_line.h"
```

add the following files to your makefile for compilation.

```shell
get_next_line.c get_next_line_utils.c
```

in order to call the function you must pass it the file descriptor of the file you want to read.

```
char *string = get_next_line(fd);
```



[![ralopez-'s 42 get_next_line Score](https://badge42.vercel.app/api/v2/cldajqyyb00760gla9rd1l22o/project/2815950)](https://github.com/JaeSeoKim/badge42)
