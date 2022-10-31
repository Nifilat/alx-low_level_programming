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

[3-strcmp.c](./3-strcmp.c) - Write a function that compares two strings.

- Prototype: int \_strcmp(char *s1, char *s2);
- Your function should work exactly like strcmp

[4-rev_array.c](./4-rev_array.c) - Write a function that reverses the content of an array of integers.

- Prototype: void reverse_array(int \*a, int n);
- Where n is the number of elements of the array

[5-string_toupper.c](./5-string_toupper.c) - Write a function that changes all lowercase letters of a string to uppercase.

- Prototype: char _string_toupper(char _);

[6-cap_string.c](./6-cap_string.c) - Write a function that capitalizes all words of a string.

- Prototype: char _cap_string(char _);
- Separators of words: space, tabulation, new line, ,, ;, ., !, ?, ", (, ), {, and }

[7-leet.c](./7-leet.c) - Write a function that encodes a string into 1337.

- Letters a and A should be replaced by 4
- Letters e and E should be replaced by 3
- Letters o and O should be replaced by 0
- Letters t and T should be replaced by 7
- Letters l and L should be replaced by 1
- Prototype: char _leet(char _);
- You can only use one if in your code
- You can only use two loops in your code
- You are not allowed to use switch
- You are not allowed to use any ternary operation

[100-rot13.c](./100-rot13.c) - Write a function that encodes a string using rot13.

- Prototype: char _rot13(char _);
- You can only use if statement once in your code
- You can only use two loops in your code
- You are not allowed to use switch
- You are not allowed to use any ternary operation

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
