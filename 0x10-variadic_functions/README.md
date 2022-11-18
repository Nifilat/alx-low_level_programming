## 0x10. C - Variadic functions

[0-sum_them_all.c](./0-sum_them_all.c) - Write a function that returns the sum of all its parameters.

- Prototype: int sum_them_all(const unsigned int n, ...);
- If n == 0, return 0

[1-print_numbers.c](./1-print_numbers.c) - Write a function that prints numbers, followed by a new line.

- Prototype: void print_numbers(const char \*separator, const unsigned int n, ...);
- where separator is the string to be printed between numbers
- and n is the number of integers passed to the function
- You are allowed to use printf
- If separator is NULL, don’t print it
- Print a new line at the end of your function

[2-print_strings.c](./2-print_strings.c) - Write a function that prints strings, followed by a new line.

- Prototype: void print_strings(const char \*separator, const unsigned int n, ...);
- where separator is the string to be printed between the strings
- and n is the number of strings passed to the function
- You are allowed to use printf
- If separator is NULL, don’t print it
- If one of the string is NULL, print (nil) instead
- Print a new line at the end of your function

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

[6-is_prime_number.c](./6-is_prime_number.c) - Write a function that returns 1 if the input integer is a prime number, otherwise return 0.

- Prototype: int is_prime_number(int n);

[100-is_palindrome.c](./100-is_palindrome.c) -Write a function that returns 1 if a string is a palindrome and 0 if not.

- Prototype: int is_palindrome(char \*s);
- An empty string is a palindrome

[101-wildcmp.c](./101-wildcmp.c) - Write a function that compares two strings and returns 1 if the strings can be considered identical, otherwise return 0.

- Prototype: int wildcmp(char *s1, char *s2);
- s2 can contain the special character \*.
- The special char \* can replace any string (including an empty string)
