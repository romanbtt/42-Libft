# Libft
This project consists of rewriting the functions of libc, understanding them and learning how to use them. This library will be used in all future projects using the C language.

## Compilation
 `make`
 
## Linking

`gcc -L. -lft main.c`
 
## Functions

|  Function | Prototype | Description |
| :-: | :-: | :-: |
| ft_atoi | int	ft_atoi(const char *nptr) | Convert a string to an integer. |
| ft_bzero | void ft_bzero(void *s, size_t n) | Zero a byte string. |
| ft_calloc | void *ft_calloc(size_t nmemb, size_t size) | A memory allocator. |
| ft_delchar | void ft_delchar(char *str, char set) | Rewrite a string without a specific char. |
| ft_delspace | void ft_delspace(char *str) | Rewrite a string without spaces. |
| ft_intlen | int ft_intlen(int nb, int base) | Calculate the lenght of an integer. |
| ft_isalnum | int ft_isalnum(int c) | Test for an alphanumeric character. |
| ft_isalpha | int ft_isalpha(int c) | Test for an alphabetic character. |
| ft_isascii | int ft_isascii(int c) | Test for an ascii character. |
| ft_isdigit | int ft_isdigit(int c) | Test for a digit character. |
| ft_isprint | int ft_isprint(int c) | Test for a printable character. |
| ft_isspace | int ft_isspace(const char c) | Test for a white-space character. |
| ft_itoa | char *ft_itoa(int n) | Convert an integer to a string. |
| ft_lstadd_back | void ft_lstadd_back(t_list **alst, t_list *new) | Add a new node at the end of a linked list. |
| ft_lstadd_front | void ft_lstadd_front(t_list **alst, t_list *new) | Add a new node at the beginning of a linked list. |
| ft_lstclear | void ft_lstclear(t_list **lst, void (*del)(void*)) | Clear a linked list and delete each element with the del function. |
| ft_lstdelone | void ft_lstdelone(t_list *lst, void (*del)(void*)) | Delete a node in a linked list with the del function. |
| ft_lstiter | void	ft_lstiter(t_list *lst, void (*f)(void *)) | Iterate each element and apply f to each one. |
| ft_lstlast | t_list *ft_lstlast(t_list *lst) | Return the last node of the linked list. |
| ft_lstmap | t_list *ft_lstmap(t_list *lst, void *(*f)(void *), void (*del)(void *)) | Create a new list of the return of f. |
| ft_lstnew | t_list *ft_lstnew(void *content) | Create a new linked list. |
| ft_lstsize | int ft_lstsize(t_list *lst) | Return the lenght of a linked list. |
| ft_memccpy | void	*ft_memccpy(void *dest, const void *src, int c, size_t n) | Copy memory area. |
| ft_memchr | void *ft_memchr(const void *s, int c, size_t n) | Scan memory for a character. |
| ft_memcmp | int ft_memcmp(const void *s1, const void *s2, size_t n) | Compare memory areas. |
| ft_memcpy | void *ft_memcpy(void *dest, const void *src, size_t n) | Copy memory area. |
| ft_memmove | void	*ft_memmove(void *dest, const void *src, size_t n) | Move memory area. |
| ft_memset | void *ft_memset(void *s, int c, size_t n) | Fill memory with a constant byte. |
| ft_putchar_fd | void ft_putchar_fd(char c, int fd) | Put a byte on fd. |
| ft_putendl_fd | void ft_putendl_fd(char *s, int fd) | Put a string follow by a newline on fd. |
| ft_putnbr_fd | void ft_putnbr_fd(int n, int fd) | Put a number on fd. |
| ft_putstr_fd | void ft_putstr_fd(char *s, int fd) | Put a string on fd. |
| ft_realloc | void	*ft_realloc(void *ptr, size_t size) | Memory reallocator. |
| ft_split_isspace | char **ft_split_isspace(char const *s) | Split a string into pieces using spaces define by ft_isspace as separator. |
| ft_split | char **ft_split(char const *s, char c) | Split a string into pieces using c as separator. |
| ft_strchr | char *ft_strchr(const char *s, int c) | Locate character in string. |
| ft_strdel | void ft_strdel(char **s) | Free and nulled a string. |
| ft_strdup | char *ft_strdup(const char *s) | Duplicate a string. |
| ft_strjoin | char	*ft_strjoin(char const *s1, char const *s2) | Join two strings. |
| ft_strlcat | size_t ft_strlcat(char *dst, const char *src, size_t size) | Concatenate two strings. |
| ft_strlcpy | size_t ft_strlcpy(char *dst, const char *src, size_t size) | Copy a string. |
| ft_strlen | size_t ft_strlen(const char *s) | Calculate the length of a string. |
| ft_strmapi | char	*ft_strmapi(char const *s, char (*f)(unsigned int, char)) | Create a new string applying f to each character. |
| ft_strncmp | int ft_strncmp(const char *s1, const char *s2, size_t n) | Compare two strings. |
| ft_strnstr | char	*ft_strnstr(const char *big, const char *little, size_t len) | Locate a substring in a string. |
| ft_strrchr | char	*ft_strrchr(const char *s, int c) | Locate character in string. |
| ft_strtrim | char	*ft_strtrim(char const *s1, char const *set) | Remove leading and trailing set of characters. |
| ft_substr | char *ft_substr(char const *s, unsigned int start, size_t len) | Return a substring of len characters begenning at start. |
| ft_swap | void ft_swap(void *a, void *b, size_t len) | Swap value of two pointers. |
| ft_tolower | int ft_tolower(int c) | Upper case to lower case letter conversion. |
| ft_toupper | int ft_toupper(int c) | Lower case to upper case letter conversion. |
| ft_uintlen | int ft_uintlen(unsigned int nb, int base) | Calculate the lenght of an unsigned integer. |
| ft_ullitoa_base | char *ft_ullitoa_base(unsigned long long int nb, int base) | Convert an unsigned long long integer to a string using a specific base. |
