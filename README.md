#   libft (core_project)

-	A recreation of the functions of the standard C library.
	This project makes you to take the time to re-write those 
	functions, understand them, and learn to use them. This 
	library will help you for all your future C projects. We
	are also given the opportunity to expand the list of functions
	with our own.

	- The only allowed functions to help recreate are:
	
	write, malloc & free.

### Compilation

-	libft is compiled with a `Makefile`; to compile, run the following command:

```
make
```
-	If edits are made to the project, it will need to be recompiled.
	To recompile run the following command:

```
make re
```
##  Usage

-	To use this library, `#include "libft.h"` will need to be added to 
	the list of included libraries & will need to be in the correct directory.
	If additional functions are added to libft, the function will need to be 
	prototyped in the `libft.h` file & libft will need to be recompiled.

### Compiling with libft.a

-	Run the following command by adding the relevant compilation files.

```
gcc [your main] [other files] [flags] libft.a
./a.out
```
