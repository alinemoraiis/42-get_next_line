# 42-get_next_line
- This project is about coding a function that allow you read a text file pointed to by the file descriptor and return one line at a time. Introduction to **static variables**.

## :sunglasses: Files
- **get_next_line.c**: file with the main functions.
- **get_next_line_utils.c**: file with helper functions.
- **get_next_line.h**: header file with all declarated functions.

## :sunglasses: Functions
- **get_next_line**: main function. Return line by line.
- **read_file**: function that read the file. Receive the fd (an int) by parameter. Called by the get_next_line.
- **get_line**: function that "save" line by line.
- **save_file**: function that update the file.
- **ft_strlen**: return the lenght of the string s, excluding the NULL character. (Copied from Libft project).
- **ft_strchr**: locates the first occurence of c in the string s and return a pointer to the located character. (Copied from Libft project).
- **ft_strjoin**: allocates memory and returns a new string, which is the result of the concatenation of s1 and s2. (Copied from Libft project).
- **ft_substr**: allocates memory and returns a new substring from the string s. The substring begins at index start and is of maximum size len. (Copied from Libft project).

## :sunglasses: Used test
- [gnlTester](https://github.com/Tripouille/gnlTester)
