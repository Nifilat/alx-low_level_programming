## 0x0B. C - malloc, free

[0-create_array.c](./0-create_array.c) - Write a function that creates an array of chars, and initializes it with a specific char.

- Prototype: char \*create_array(unsigned int size, char c);
- Returns NULL if size = 0
- Returns a pointer to the array, or NULL if it fails

[1-strdup.c](./1-strdup.c) - Write a function that returns a pointer to a newly allocated space in memory, which contains a copy of the string given as a parameter.

- Prototype: char *\_strdup(char *str);
- The \_strdup() function returns a pointer to a new string which is a duplicate of the string str. Memory for the new string is obtained with malloc, and can be freed with free.
- Returns NULL if str = NULL
- On success, the \_strdup function returns a pointer to the duplicated string. It returns NULL if insufficient memory was available

FYI: The standard library provides a similar function: strdup. Run man strdup to learn more.

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

[100-change.c](./100-change.c) - Write a program that prints the minimum number of coins to make change for an amount of money.

- Usage: ./change cents
- where cents is the amount of cents you need to give back
- if the number of arguments passed to your program is not exactly 1, print Error, followed by a new line, and return 1
- you should use atoi to parse the parameter passed to your program
- If the number passed as the argument is negative, print 0, followed by a new line
- You can use an unlimited number of coins of values 25, 10, 5, 2, and 1 cent
