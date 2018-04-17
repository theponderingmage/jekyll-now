---
layout: post
title: The Second Day of Our C Voyage
---
Welcome to the second day of our C voyage. Today, Sharls and Teddy are going to explore further; how to program in C.

## Revision of what we know so far
Sharls made her first C program yesterday. She did this by first typing out a program in :memo:**Text Edit**.
The program was typed in as plain text (**CMD + Shift + T**).
```c
/* hello.c */
#include <stdio.h>

int main(void)
{
	printf("Hello, World!\n");
	
	return 0;
}
```
Sharls then saved the file :floppy_disk: with a `.c` extension.
She then compiled it using the command `cc hello.c -o program`.
Sharls then went on to execute the program with the command `./program`.

## Revision Questions
**What is the basic structure of a C program?**

**What does the command `#include <stdio.h>` do?**

**What is the command issued to the terminal to compile a program?**

**Explain the function header `int main(void)`?**

**What does `return 0;` mean?**

**Spot the error in the code:**
```c
#include <stdio.h>

int main(void)
{
	printf("Hello, World!\n")
	
	return 0
}
```
