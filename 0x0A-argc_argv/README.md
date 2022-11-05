## 0x0A. C - argc, argv

[0-whatsmyname.c](./0-whatsmyname.c) - Write a program that prints its name, followed by a new line.

- If you rename the program, it will print the new name, without having to compile it again
- You should not remove the path before the name of the program

[1-args.c](./1-args.c) - Write a program that prints the number of arguments passed into it.

- Your program should print a number, followed by a new line

[2-args.c](./2-args.c) - Write a program that prints all arguments it receives.

- All arguments should be printed, including the first one
- Only print one argument per line, ending with a new line

[3-mul.c](./3-mul.c) - Write a program that multiplies two numbers.

- Your program should print the result of the multiplication, followed by a new line
- You can assume that the two numbers and result of the multiplication can be stored in an integer
- If the program does not receive two arguments, your program should print Error, followed by a new line, and return 1

[4-add.c](./4-add.c) - Write a program that adds positive numbers.

- Print the result, followed by a new line
- If no number is passed to the program, print 0, followed by a new line
- If one of the number contains symbols that are not digits, print Error, followed by a new line, and return 1
- You can assume that numbers and the addition of all the numbers can be stored in an int

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
