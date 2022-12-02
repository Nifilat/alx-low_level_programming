## 0x12. C - Singly linked lists

[0-print_list.c](./0-print_list.c) - Write a function that prints all the elements of a list_t list.

- Prototype: size_t print_list(const list_t \*h);
- Return: the number of nodes
- Format: see example
- If str is NULL, print [0] (nil)
- You are allowed to use printf

[1-list_len.c](./1-list_len.c) - Write a function that returns the number of elements in a linked list_t list.

- Prototype: size_t list_len(const list_t \*h);

[2-add_node.c](./2-add_node.c) - Write a function that adds a new node at the beginning of a list_t list.

- Prototype: list_t *add_node(list_t \*\*head, const char *str);
- Return: the address of the new element, or NULL if it failed
- str needs to be duplicated
- You are allowed to use strdup

[3-print_all.c](./3-print_all.c) - Write a function that prints anything.

- Prototype: void print_all(const char \* const format, ...);
- where format is a list of types of arguments passed to the function
  - c: char
  - i: integer
  - f: float
  - s: char \* (if the string is NULL, print (nil) instead
  - any other char should be ignored
  - see example
- You are not allowed to use for, goto, ternary operator, else, do ... while
- You can use a maximum of
  - 2 while loops
  - 2 if
- You can declare a maximum of 9 variables
- You are allowed to use printf
- Print a new line at the end of your function
