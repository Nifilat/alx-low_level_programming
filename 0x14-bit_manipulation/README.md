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

[5-free_listint2.c](./5-free_listint2.c) - Write a function that frees a listint_t list.

- Prototype: void free_listint2(listint_t \*\*head);
- The function sets the head to NULL

[6-pop_listint.c](./6-pop_listint.c) - Write a function that deletes the head node of a listint_t linked list, and returns the head node’s data (n).

- Prototype: int pop_listint(listint_t \*\*head);
- if the linked list is empty return 0

[7-get_nodeint.c](./7-get_nodeint.c) - Write a function that returns the nth node of a listint_t linked list.

Prototype: listint_t *get_nodeint_at_index(listint_t *head, unsigned int index);
where index is the index of the node, starting at 0
if the node does not exist, return NULL

[8-sum_listint.c](./8-sum_listint.c) - Write a function that returns the sum of all the data (n) of a listint_t linked list.

- Prototype: int sum_listint(listint_t \*head);
- if the list is empty, return 0

[9-insert_nodeint.c](./9-insert_nodeint.c) - Write a function that inserts a new node at a given position.

- Prototype: listint_t \*insert_nodeint_at_index(listint_t \*\*head, unsigned int idx, int n);
- where idx is the index of the list where the new node should be added. Index starts at 0
- Returns: the address of the new node, or NULL if it failed
- if it is not possible to add the new node at index idx, do not add the new node and return NULL

[10-delete_nodeint.c](./10-delete_nodeint.c) - Write a function that deletes the node at index index of a listint_t linked list.

- Prototype: int delete_nodeint_at_index(listint_t \*\*head, unsigned int index);
- where index is the index of the node that should be deleted. Index starts at 0
- Returns: 1 if it succeeded, -1 if it failed

[100-reverse_listint.c](./100-reverse_listint.c) - Write a function that reverses a listint_t linked list.

- Prototype: listint_t \*reverse_listint(listint_t \*\*head);
- Returns: a pointer to the first node of the reversed list
- You are not allowed to use more than 1 loop.
- You are not allowed to use malloc, free or arrays
- You can only declare a maximum of two variables in your function

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
