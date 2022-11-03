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

[4-pow_recursion.c](./4-pow_recursion.c) - Write a function that returns the value of x raised to the power of y.

- Prototype: int \_pow_recursion(int x, int y);
- If y is lower than 0, the function should return -1

FYI: The standard library provides a different function: pow. Run man pow to learn more.

[5-sqrt_recursion.c](./5-sqrt_recursion.c) - Write a function that returns the natural square root of a number.

- Prototype: int \_sqrt_recursion(int n);
- If n does not have a natural square root, the function should return -1

FYI: The standard library provides a different function: sqrt. Run man sqrt to learn more.

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
