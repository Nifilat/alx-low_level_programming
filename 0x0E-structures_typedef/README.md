## 0x0E. C - Structures, typedef

[dog.h](./dog.h) - Define a new type struct dog with the following elements:

- name, type = char \*
- age, type = float
- owner, type = char \*

[1-init_dog.c](./1-init_dog.c) - Write a function that initialize a variable of type struct dog

- Prototype: void init_dog(struct dog *d, char *name, float age, char \*owner);

[2-print_dog.c](./2-print_dog.c) - Write a function that prints a struct dog

- Prototype: void print_dog(struct dog \*d);
- Format: see example bellow
- You are allowed to use the standard library
- If an element of d is NULL, print (nil) instead of this element. (if name is NULL, print Name: (nil))
- If d is NULL print nothing.

[3-function_like_macro.h](./3-function_like_macro.h) - Write a function-like macro ABS(x) that computes the absolute value of a number x.

[4-sum.h](./4-sum.h) - Write a function-like macro SUM(x, y) that computes the sum of the numbers x and y.
