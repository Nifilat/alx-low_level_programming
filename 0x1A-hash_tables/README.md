## 0x1A. C - Hash tables

[0-hash_table_create.c](./0-hash_table_create.c) - Write a function that creates a hash table.

- Prototype: hash_table_t \*hash_table_create(unsigned long int size);
  - where size is the size of the array
- Returns a pointer to the newly created hash table
- If something went wrong, your function should return NULL

[1-djb2.c](./1-djb2.c) - Write a hash function implementing the djb2 algorithm.

Prototype: unsigned long int hash_djb2(const unsigned char \*str);
You are allowed to copy and paste the function from [this page](https://gist.github.com/papamuziko/7bb52dfbb859fdffc4bd0f95b76f71e8)

[2-key_index.c](./2-key_index.c) - Write a function that gives you the index of a key.

- Prototype: unsigned long int key_index(const unsigned char \*key, unsigned long int size);
  - where key is the key
  - and size is the size of the array of the hash table
- This function should use the hash_djb2 function that you wrote earlier
- Returns the index at which the key/value pair should be stored in the array of the hash table
- You will have to use this hash function for all the next tasks

[3-hash_table_set.c](./3-hash_table_set.c) - Write a function that adds an element to the hash table.

- Prototype: int hash_table_set(hash_table_t *ht, const char *key, const char \*value);
  - Where ht is the hash table you want to add or update the key/value to
  - key is the key. key can not be an empty string
  - and value is the value associated with the key. value must be duplicated. value can be an empty string
- Returns: 1 if it succeeded, 0 otherwise
- In case of collision, add the new node at the beginning of the list

[4-hash_table_get.c](./4-hash_table_get.c) - Write a function that retrieves a value associated with a key.

- Prototype: char *hash_table_get(const hash_table_t *ht, const char \*key);
  - where ht is the hash table you want to look into
  - and key is the key you are looking for
- Returns the value associated with the element, or NULL if key couldn’t be found

[5-hash_table_print.c](./5-hash_table_print.c) - Write a function that prints a hash table.

- Prototype: void hash_table_print(const hash_table_t \*ht);
  - where ht is the hash table
- You should print the key/value in the order that they appear in the array of hash table
  - Order: array, list
- Format: see example
- If ht is NULL, don’t print anything

[6-print_numberz.c](./6-print_numberz.c) - Write a program that prints all single digit numbers of base 10 starting from 0, followed by a new line.

- You are not allowed to use any variable of type char
- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- You can only use putchar twice in your code
- All your code should be in the main function

[7-print_tebahpla.c](./7-print_tebahpla.c) - Write a program that prints the lowercase alphabet in reverse, followed by a new line.

- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- All your code should be in the main function
- You can only use putchar twice in your code

[8-print_base16.c](./8-print_base16.c) - Write a program that prints all the numbers of base 16 in lowercase, followed by a new line.

- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- All your code should be in the main function
- You can only use putchar three times in your code

[9-print_comb.c](./9-print_comb.c) - Write a program that prints all possible combinations of single-digit numbers.

- Numbers must be separated by ,, followed by a space
- Numbers should be printed in ascending order
- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- All your code should be in the main function
- You can only use putchar four times maximum in your code
- You are not allowed to use any variable of type char

[100-print_comb3.c](./100-print_comb3.c) - Write a program that prints all possible different combinations of two digits.

- Numbers must be separated by ,, followed by a space
- The two digits must be different
- 01 and 10 are considered the same combination of the two digits 0 and 1
- Print only the smallest combination of two digits
- Numbers should be printed in ascending order, with two digits
- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- You can only use putchar five times maximum in your code
- You are not allowed to use any variable of type char
- All your code should be in the main function

[101-print_comb4.c](./101-print_comb4.c) - Write a program that prints all possible different combinations of three digits.

- Numbers must be separated by ,, followed by a space
- The three digits must be different
- 012, 120, 102, 021, 201, 210 are considered the same combination of the three digits 0, 1 and 2
- Print only the smallest combination of three digits
- Numbers should be printed in ascending order, with three digits
- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- You can only use putchar six times maximum in your code
- You are not allowed to use any variable of type char
- All your code should be in the main function

[102-print_comb5.c](./102-print_comb5.c) - Write a program that prints all possible combinations of two two-digit numbers.

- The numbers should range from 0 to 99
- The two numbers should be separated by a space
- All numbers should be printed with two digits. 1 should be printed as 01
- The combination of numbers must be separated by comma, followed by a space
- The combinations of numbers should be printed in ascending order
- 00 01 and 01 00 are considered as the same combination of the numbers 0 and 1
- You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
- You can only use putchar eight times maximum in your code
- You are not allowed to use any variable of type char
- All your code should be in the main function
