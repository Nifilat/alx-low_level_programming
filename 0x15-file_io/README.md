## 0x15. C - File I/O

[0-read_textfile.c](./0-read_textfile.c) - Write a function that reads a text file and prints it to the POSIX standard output.

- Prototype: ssize_t read_textfile(const char \*filename, size_t letters);
- where letters is the number of letters it should read and print
- returns the actual number of letters it could read and print
- if the file can not be opened or read, return 0
- if filename is NULL return 0
- if write fails or does not write the expected amount of bytes, return 0

[1-create_file.c](./1-create_file.c) - Create a function that creates a file.

- Prototype: int create_file(const char *filename, char *text_content);
- where filename is the name of the file to create and text_content is a NULL terminated string to write to the file
- Returns: 1 on success, -1 on failure (file can not be created, file can not be written, write “fails”, etc…)
- The created file must have those permissions: rw-------. If the file already exists, do not change the permissions.
- if the file already exists, truncate it
- if filename is NULL return -1
- if text_content is NULL create an empty file

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

[101-password](./101-password) - Find the password for [this program](https://github.com/holbertonschool/0x13.c).

- Save the password in the file 101-password
- Your file should contain the exact password, no new line, no extra space
