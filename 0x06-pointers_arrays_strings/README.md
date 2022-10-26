## 0x06. C - More pointers, arrays and strings

[0-strcat.c](./0-strcat.c) - Write a function that concatenates two strings.

- Prototype: char *\_strcat(char *dest, char \*src);
- This function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte
- Returns a pointer to the resulting string dest

[1-strncat.c](./1-strncat.c) - Write a function that concatenates two strings.

- Prototype: char *\_strncat(char *dest, char \*src, int n);
- The \_strncat function is similar to the \_strcat function, except that
- - it will use at most n bytes from src; and
- - src does not need to be null-terminated if it contains n or more bytes
- Return a pointer to the resulting string dest

[2-strncpy.c](./2-strncpy.c) - Write a function that copies a string.

- Prototype: char *\_strncpy(char *dest, char \*src, int n);
- Your function should work exactly like strncpy

[3-strcmp.c](./3-strcmp.c) - Write a function that compares two strings.

- Prototype: int \_strcmp(char *s1, char *s2);
- Your function should work exactly like strcmp

[4-rev_array.c](./4-rev_array.c) - Write a function that reverses the content of an array of integers.

- Prototype: void reverse_array(int \*a, int n);
- Where n is the number of elements of the array

[5-string_toupper.c](./5-string_toupper.c) - Write a function that changes all lowercase letters of a string to uppercase.

- Prototype: char _string_toupper(char _);

[6-puts2.c](./6-puts2.c) - Write a function that prints every other character of a string, starting with the first character, followed by a new line.

- Prototype: void puts2(char \*str);

[7-puts_half.c](./7-puts_half.c) - Write a function that prints half of a string, followed by a new line.

- Prototype: void puts_half(char \*str);
- The function should print the second half of the string
- If the number of characters is odd, the function should print the last n characters of the string, where n = (length_of_the_string - 1) / 2

[8-print_array.c](./8-print_array.c) - Write a function that prints n elements of an array of integers, followed by a new line.

- Prototype: void print_array(int \*a, int n);
- where n is the number of elements of the array to be printed
- Numbers must be separated by comma, followed by a space
- The numbers should be displayed in the same order as they are stored in the array
- You are allowed to use printf

[9-strcpy.c](./9-strcpy.c) -

- Prototype: char *\_strcpy(char *dest, char \*src);
  Write a function that copies the string pointed to by src, including the terminating null byte (\0), to the buffer pointed to by dest.

- Return value: the pointer to dest

[100-atoi.c](./100-atoi.c) - Write a function that convert a string to an integer.

- Prototype: int \_atoi(char \*s);
- The number in the string can be preceded by an infinite number of characters
- You need to take into account all the - and + signs before the number
- If there are no numbers in the string, the function must return 0
- You are not allowed to use long
- You are not allowed to declare new variables of “type” array
- You are not allowed to hard-code special values
- We will use the -fsanitize=signed-integer-overflow gcc flag to compile your code.

[101-keygen.c](./101-keygen.c) - Create a program that generates random valid passwords for the program 101-crackme.

- You are allowed to use the standard library
- You don’t have to pass the betty-style tests (you still need to pass the betty-doc tests)
- man srand, rand, time
- gdb and objdump can help
