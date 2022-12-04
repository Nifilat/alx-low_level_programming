## 0x14. C - Bit manipulation

[0-binary_to_uint.c](./0-binary_to_uint.c) - Write a function that converts a binary number to an unsigned int.

- Prototype: unsigned int binary_to_uint(const char \*b);
- where b is pointing to a string of 0 and 1 chars
- Return: the converted number, or 0 if
  - there is one or more chars in the string b that is not 0 or 1
  - b is NULL

[1-print_binary.c](./1-print_binary.c) - Write a function that prints the binary representation of a number.

- Prototype: void print_binary(unsigned long int n);
- Format: see example
- You are not allowed to use arrays
- You are not allowed to use malloc
- You are not allowed to use the % or / operators

[2-get_bit.c](./2-get_bit.c) - Write a function that returns the value of a bit at a given index.

- Prototype: int get_bit(unsigned long int n, unsigned int index);
- where index is the index, starting from 0 of the bit you want to get
- Returns: the value of the bit at index index or -1 if an error occured

[3-set_bit.c](./3-set_bit.c) - Write a function that sets the value of a bit to 1 at a given index.

- Prototype: int set_bit(unsigned long int \*n, unsigned int index);
- where index is the index, starting from 0 of the bit you want to set
- Returns: 1 if it worked, or -1 if an error occurred

[4-clear_bit.c](./4-clear_bit.c) - Write a function that sets the value of a bit to 0 at a given index.

- Prototype: int clear_bit(unsigned long int \*n, unsigned int index);
- where index is the index, starting from 0 of the bit you want to set
- Returns: 1 if it worked, or -1 if an error occurred

[5-flip_bits.c](./5-flip_bits.c) - Write a function that returns the number of bits you would need to flip to get from one number to another.

- Prototype: unsigned int flip_bits(unsigned long int n, unsigned long int m);
- You are not allowed to use the % or / operators

[100-get_endianness.c](./100-get_endianness.c) - Write a function that checks the endianness.

- Prototype: int get_endianness(void);
- Returns: 0 if big endian, 1 if little endian

[101-print_listint_safe.c](./101-print_listint_safe.c) - Write a function that prints a listint_t linked list.

- Prototype: size_t print_listint_safe(const listint_t \*head);
- Returns: the number of nodes in the list
- This function can print lists with a loop
- You should go through the list only once
- If the function fails, exit the program with status 98

[102-free_listint_safe.c](./102-free_listint_safe.c) - Write a function that frees a listint_t list.

- Prototype: size_t free_listint_safe(listint_t \*\*h);
- This function can free lists with a loop
- You should go though the list only once
- Returns: the size of the list that was free’d
- The function sets the head to NULL

[103-find_loop.c](./103-find_loop.c) - Write a function that finds the loop in a linked list.

- Prototype: listint_t *find_listint_loop(listint_t *head);
- Returns: The address of the node where the loop starts, or NULL if there is no loop
- You are not allowed to use malloc, free or arrays
- You can only declare a maximum of two variables in your function
