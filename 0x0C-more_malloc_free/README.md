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

[2-str_concat.c](./2-str_concat.c) - Write a function that concatenates two strings.

- Prototype: char *str_concat(char *s1, char \*s2);
- The returned pointer should point to a newly allocated space in memory which contains the contents of s1, followed by the contents of s2, and null terminated
- if NULL is passed, treat it as an empty string
- The function should return NULL on failure

[3-alloc_grid.c](./3-alloc_grid.c) - Write a function that returns a pointer to a 2 dimensional array of integers.

- Prototype: int \*\*alloc_grid(int width, int height);
- Each element of the grid should be initialized to 0
- The function should return NULL on failure
- If width or height is 0 or negative, return NULL

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
