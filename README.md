# Libft
This project consists of rewriting the functions of libc, understanding them and learning how to use them. This library will be used in all future projects using the C language.

|  Function | Prototype | Description |
| :-: | :-: | :-: |
| ft_atoi | int	ft_atoi(const char *nptr) | Convert a string to an integer |
| ft_bzero | void ft_bzero(void *s, size_t n) | Zero a byte string |
| ft_calloc | void *ft_calloc(size_t nmemb, size_t size) | A memory allocator |
| ft_delchar | void ft_delchar(char *str, char set) | Rewrite a string without a specific char |
| ft_delspace | void ft_delspace(char *str) | Rewrite a string without spaces |
| ft_intlen | int ft_intlen(int nb, int base) | Count the lenght of an integer |
| ft_isalnum | int ft_isalnum(int c) | Test for an alphanumeric character |
| ft_isalpha | int ft_isalpha(int c) | Test for an alphabetic character |
| ft_isascii | int ft_isascii(int c) | Test for an ascii character |
| ft_isdigit | int ft_isdigit(int c) | Test for a digit character |
| ft_isprint | int ft_isprint(int c) | Test for a printable character |
| ft_isspace | int ft_isspace(const char c) | Test for a white-space character |
| ft_itoa | char *ft_itoa(int n) | Convert an integer to a string |
| ft_lstadd_back | void ft_lstadd_back(t_list **alst, t_list *new) | Add new node at the end of a linked list |
| ft_lstadd_front | void ft_lstadd_front(t_list **alst, t_list *new) | Add new node at the beginning of a linked list |
| ft_lstclear | void ft_lstclear(t_list **lst, void (*del)(void*)) | Clear a linked list and delete each element with the del function passed in parameter |
| ft_lstdelone | void ft_lstdelone(t_list *lst, void (*del)(void*)) | Delete a node in a linked list with the del function passed in parameter |
| ft_lstiter | void	ft_lstiter(t_list *lst, void (*f)(void *)) | Iterate each element and send the content to the function f passed in parameter |
| ft_lstlast | t_list *ft_lstlast(t_list *lst) | Return the last node of the linked list |
| ft_lstmap | t_list *ft_lstmap(t_list *lst, void *(*f)(void *), void (*del)(void *)) | Create a new linked list with the result of the return of the function f of each node. The node is delete if needed. |
| ft_lstnew | t_list *ft_lstnew(void *content) | Create a new linked list |
| ft_lstsize | int ft_lstsize(t_list *lst) | Return the lenght of a linked list |
| ft_memccpy | void	*ft_memccpy(void *dest, const void *src, int c, size_t n) | Copy no more than n bytes from memory area src to memory area dest, stopping when the character c is found |
| ft_memchr | void	*ft_memchr(const void *s, int c, size_t n) | Scan the initial n bytes of the memory area pointed to by the string for the first instance of the char |
| ft_memcmp | int ft_memcmp(const void *s1, const void *s2, size_t n) | Compare the first n bytes of the memory areas of the first string and the second |
| ft_memcpy | void	*ft_memcpy(void *dest, const void *src, size_t n) | Copy n bytes from memory area src to memory area dest |

| ft_memmove | upper case to lower case letter conversion |
| ft_memset | lower case to upper case letter conversion |
| ft_putchar_fd | checks for any printable character including space |
| ft_putendl_fd | checks for white-space characters |
| ft_split_isspace | upper case to lower case letter conversion |
| ft_split | lower case to upper case letter conversion |
| ft_strchr | checks for an alphanumeric character |
| ft_strdel | checks for an alphabetic character |
| ft_strdup | checks for a digit (0 through 9) |
| ft_strjoin | checks for any printable character including space |
| ft_strlcat | checks for white-space characters |
| ft_strlcpy | upper case to lower case letter conversion |
| ft_strlen | lower case to upper case letter conversion |
| ft_strmapi | checks for any printable character including space |
| ft_strncmp | checks for white-space characters |
| ft_strnstr | upper case to lower case letter conversion |
| ft_strrchr | lower case to upper case letter conversion |
| ft_strtrim | checks for an alphanumeric character |
| ft_substr | checks for an alphabetic character |
| ft_swap | checks for a digit (0 through 9) |
| ft_tolower | checks for any printable character including space |
| ft_toupper | checks for white-space characters |
| ft_uintlen | upper case to lower case letter conversion |
| ft_ullitoa_base | lower case to upper case letter conversion |
