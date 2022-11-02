## 0x08. C - Recursion

[0-puts_recursion.c](./0-puts_recursion.c) - Write a function that prints a string, followed by a new line.

- Prototype: void \_puts_recursion(char \*s);

FYI: The standard library provides a similar function: puts. Run man puts to learn more.

[1-print_rev_recursion.c](./1-print_rev_recursion.c) - Write a function that prints a string in reverse.

- Prototype: void \_print_rev_recursion(char \*s);

[2-strlen_recursion.c](./2-strlen_recursion.c) - Write a function that returns the length of a string.

- Prototype: int \_strlen_recursion(char \*s);

FYI: The standard library provides a similar function: strlen. Run man strlen to learn more.

[3-factorial.c](./3-factorial.c) - Write a function that returns the factorial of a given number.

- Prototype: int factorial(int n);
- If n is lower than 0, the function should return -1 to indicate an error
- Factorial of 0 is 1

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

[101-crackme_password](./101-crackme_password) - Create a file that contains the password for the [crackme2](https://github.com/holbertonschool/0x06.c) executable.

- Your file should contain the exact password, no new line, no extra space
- ltrace, ldd, gdb and objdump can help
- You may need to install the openssl library to run the crakme2 program: sudo apt install libssl-dev
- Edit the source list sudo nano /etc/apt/sources.list to add the following line: deb http://security.ubuntu.com/ubuntu xenial-security main Then sudo apt update and sudo apt install libssl1.0.0
