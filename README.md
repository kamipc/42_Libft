Project Libft

Module 0 of 42 Common Core

Mandatory objective: 

Create my own library that includes my own implementation of multiple functions that will then be available to 
use in future projects.
The following ones have to behave exactly as their known counterpart:

• isalpha
• isdigit
• isalnum
• isascii
• isprint
• strlen
• memset
• bzero
• memcpy
• memmove
• strlcpy
• strlcat
• toupper
• tolower
• strchr
• strrchr
• strncmp
• memchr
• memcmp
• strnstr
• atoi
• calloc
• strdup

and additional functions:

• ft_substr
• ft_strjoin
• ft_strtrim
• ft_split
• ft_itoa
• ft_ismapi
• ft_striteri
• ft_putchar_fd
• ft_putstr_fd
• ft_putendl_fd
• ft_putnbr_fd

Bonus Objective:

The bonus objective is about functions to deal with lists.
The list will have the following structure which should be added to the .h:

typedef struct s_list
{
void *content;
struct s_list *next;
} t_list;

the functions will be:

• ft_lstnew
• ft_lstadd_front
• ft_lstsize
• ft_lstlast
• ft_lstadd_back
• ft_lstdelone
• ft_lstclear
• ft_lstiter
• ft_lstmap

![image](https://github.com/user-attachments/assets/c0d23ba5-7a1a-4415-ac77-e10ae47253b0)