## 0x0B. C - malloc, free

[0-malloc_checked.c](./0-malloc_checked.c) - Write a function that allocates memory using malloc.

- Prototype: void \*malloc_checked(unsigned int b);
- Returns a pointer to the allocated memory
- if malloc fails, the malloc_checked function should cause normal process termination with a status value of 98

[1-string_nconcat.c](./1-string_nconcat.c) - Write a function that concatenates two strings.

- Prototype: char *string_nconcat(char *s1, char \*s2, unsigned int n);
- The returned pointer shall point to a newly allocated space in memory, which contains s1, followed by the first n bytes of s2, and null terminated
- If the function fails, it should return NULL
- If n is greater or equal to the length of s2 then use the entire string s2
- if NULL is passed, treat it as an empty string

[2-calloc.c](./2-calloc.c) - Write a function that allocates memory for an array, using malloc.

- Prototype: void \*\_calloc(unsigned int nmemb, unsigned int size);
- The \_calloc function allocates memory for an array of nmemb elements of size bytes each and returns a pointer to the allocated memory.
- The memory is set to zero
- If nmemb or size is 0, then \_calloc returns NULL
- If malloc fails, then \_calloc returns NULL

FYI: The standard library provides a different function: calloc. Run man calloc to learn more.

[3-array_range.c](./3-array_range.c) - Write a function that creates an array of integers.

- Prototype: int \*array_range(int min, int max);
- The array created should contain all the values from min (included) to max (included), ordered from min to max
- Return: the pointer to the newly created array
- If min > max, return NULL
- If malloc fails, return NULL

[4-free_grid.c](./4-free_grid.c) - Write a function that frees a 2 dimensional grid previously created by your alloc_grid function.

- Prototype: void free_grid(int \*\*grid, int height);
- Note that we will compile with your alloc_grid.c file. Make sure it compiles.

[100-argstostr.c](./100-argstostr.c) - Write a function that concatenates all the arguments of your program.

- Prototype: char \*argstostr(int ac, char \*\*av);
- Returns NULL if ac == 0 or av == NULL
- Returns a pointer to a new string, or NULL if it fails
- Each argument should be followed by a \n in the new string

[101-strtow.c](./101-strtow.c) - Write a function that splits a string into words.

- Prototype: char \**strtow(char *str);
- The function returns a pointer to an array of strings (words)
- Each element of this array should contain a single word, null-terminated
- The last element of the returned array should be NULL
- Words are separated by spaces
- Returns NULL if str == NULL or str == ""
- If your function fails, it should return NULL
