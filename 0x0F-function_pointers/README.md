## 0x0F. C - Function pointers

[0-print_name.c](./0-print_name.c) - Write a function that prints a name.

- Prototype: void print_name(char *name, void (*f)(char \*));

[1-array_iterator.c](./1-array_iterator.c) - Write a function that executes a function given as a parameter on each element of an array.

- Prototype: void array_iterator(int *array, size_t size, void (*action)(int));
- where size is the size of the array
- and action is a pointer to the function you need to use

[2-print_dog.c](./2-print_dog.c) - Write a function that prints a struct dog

- Prototype: void print_dog(struct dog \*d);
- Format: see example bellow
- You are allowed to use the standard library
- If an element of d is NULL, print (nil) instead of this element. (if name is NULL, print Name: (nil))
- If d is NULL print nothing.

[4-new_dog.c](./4-new_dog.c) - Write a function that creates a new dog.

- Prototype: dog_t *new_dog(char *name, float age, char \*owner);
- You have to store a copy of name and owner
- Return NULL if the function fails

[5-free_dog.c](./5-free_dog.c) - Write a function that frees dogs.

- Prototype: void free_dog(dog_t \*d);
