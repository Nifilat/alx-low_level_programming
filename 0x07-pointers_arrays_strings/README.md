## 0x07. C - Even more pointers, arrays and strings

[0-memset.c](./0-memset.c) - Write a function that fills memory with a constant byte.

- Prototype: char *\_memset(char *s, char b, unsigned int n);
- The \_memset() function fills the first n bytes of the memory area pointed to by s with the constant byte b
- Returns a pointer to the memory area s

[1-memcpy.c](./1-memcpy.c) - Write a function that copies memory area.

- Prototype: char *\_memcpy(char *dest, char \*src, unsigned int n);
- The \_memcpy() function copies n bytes from memory area src to memory area dest
- Returns a pointer to dest

[2-strchr.c](./2-strchr.c) - Write a function that locates a character in a string.

- Prototype: char *\_strchr(char *s, char c);
- Returns a pointer to the first occurrence of the character c in the string s, or NULL if the character is not found

[3-strspn.c](./3-strspn.c) - Write a function that gets the length of a prefix substring.

- Prototype: unsigned int \_strspn(char *s, char *accept);
- Returns the number of bytes in the initial segment of s which consist only of bytes from accept

FYI: The standard library provides a similar function: strspn. Run man strspn to learn more.

[4-strpbrk.c](./4-strpbrk.c) - Write a function that searches a string for any of a set of bytes.

- Prototype: char *\_strpbrk(char *s, char \*accept);
- The \_strpbrk() function locates the first occurrence in the string s of any of the bytes in the string accept
- Returns a pointer to the byte in s that matches one of the bytes in accept, or NULL if no such byte is found

FYI: The standard library provides a similar function: strpbrk. Run man strpbrk to learn more.

[5-strstr.c](./5-strstr.c) - Write a function that locates a substring.

- Prototype: char *\_strstr(char *haystack, char \*needle);
- The \_strstr() function finds the first occurrence of the substring needle in the string haystack. The terminating null bytes (\0) are not compared
- Returns a pointer to the beginning of the located substring, or NULL if the substring is not found.

FYI: The standard library provides a similar function: strstr. Run man strstr to learn more.

[7-print_chessboard.c](./7-print_chessboard.c) - Write a function that prints the chessboard.

- Prototype: void print_chessboard(char (\*a)[8]);

[8-print_diagsums.c](./8-print_diagsums.c) - Write a function that prints the sum of the two diagonals of a square matrix of integers.

- Prototype: void print_diagsums(int \*a, int size);
- Format: see example
- You are allowed to use the standard library

[100-set_string.c](./100-set_string.c) -Write a function that sets the value of a pointer to a char.

- Prototype: void set_string(char \**s, char *to);

[101-print_number.c](./101-print_number.c) - Write a function that prints an integer.

- Prototype: void print_number(int n);
- You can only use \_putchar function to print
- You are not allowed to use long
- You are not allowed to use arrays or pointers
- You are not allowed to hard-code special values

[102-magic.c](./102-magic.c) - Add one line to [this code](https://github.com/holbertonschool/make_magic_happen/blob/master/magic.c), so that the program prints a[2] = 98, followed by a new line.

- You are not allowed to use the variable a in your new line of code
- You are not allowed to modify the variable p
- You can only write one statement
- You are not allowed to use ,
- You are not allowed to code anything else than the line of expected line of code at the expected line
- Your code should be written at line 19, before the ;
- Do not remove anything from the initial code (not even the comments)
- and don’t change anything but the line of code you are adding (don’t change the spaces to tabs!)
- You are allowed to use the standard library

[103-infinite_add.c](./103-infinite_add.c) - Write a function that adds two numbers.

- Prototype: char *infinite_add(char *n1, char *n2, char *r, int size_r);
- Where n1 and n2 are the two numbers
- r is the buffer that the function will use to store the result
- size_r is the buffer size
- The function returns a pointer to the result
- You can assume that you will always get positive numbers, or 0
- You can assume that there will be only digits in the strings n1 and n2
- n1 and n2 will never be empty
- If the result can not be stored in r the function must return 0

[104-print_buffer.c](./104-print_buffer.c) - Write a function that prints a buffer.

- Prototype: void print_buffer(char \*b, int size);
- The function must print the content of size bytes of the buffer pointed by b
- The output should print 10 bytes per line
- Each line starts with the position of the first byte of the line in hexadecimal (8 chars), starting with 0
- Each line shows the hexadecimal content (2 chars) of the buffer, 2 bytes at a time, separated by a space
- Each line shows the content of the buffer. If the byte is a printable character, print the letter, if not, print .
- Each line ends with a new line \n
- If size is 0 or less, the output should be a new line only \n
- You are allowed to use the standard library
- The output should look like the following example, and formatted exactly the same way:
