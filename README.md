# 42LIBFT-PROJECT : 🧰 libft
YOUR VERY FIRST OWN LIBRARY ---- >> This project is your first project as a student at 42. You will need to recode a few functions of the C standard library as well as some other utility functions that you will use during your whole cursus.
# ABOUT LIBFT-PROJECT :
Programming in C can be very tedious when you don't have access to the very useful standard functions.
This project gives you the opportunity to rewrite those functions to understand them and learn to use them.
The library will help you for your future projects in C. Through this project, you have the opportunity
to extend your list of functions in your own way! For more detailed information, look at the subject of this project.

⚠️ NOTE ⚠️ : To be successful with moulinette on this project I had to put all the files in the same directory. I have just put them in folders and modified the Makefile to have a better organized repository.
# LIST OF FUNCTIONS :

---> Functions from <ctype.h> library

ୡ [ft_isascii](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isascii.c) - test for ASCII character.                                         
ୡ [ft_isalnum](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isalnum.c) - alphanumeric character test.                                    
ୡ [ft_isalpha](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isalpha.c) - alphabetic character test.                                      
ୡ [ft_isdigit](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isdigit.c) - decimal-digit character test.                                    
ୡ [ft_isprint](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isprint.c) - printing character test (space character inclusive).            
ୡ [ft_tolower](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_tolower.c) - upper case to lower case letter conversion.                      
ୡ [ft_toupper](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_toupper.c) - lower case to upper case letter conversion.                      

---> Functions from <stdlib.h> library

ୡ [ft_atoi](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_atoi.c) - convert ASCII string to integer.                                    
ୡ [ft_calloc](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_calloc.c) - memory allocation.

---> Functions from <strings.h> library

ୡ [ft_bzero](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_bzero.c) - write zeroes to a byte string.                                      
ୡ [ft_memset](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memset.c) - write a byte to a byte string.                                    
ୡ [ft_memchr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memchr.c) - locate byte in byte string.                                        
ୡ [ft_memcmp](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memcmp.c)- compare byte string.                                                
ୡ [ft_memove](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memove.c) - copy byte string.                                                  
ୡ [ft_memcpy](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memcpy.c) - copy memory area.                                                  

---> Functions from <string.h> library

ft_strlen - find length of string.
ft_strchr - locate character in string (first occurrence).
ft_strrchr - locate character in string (last occurence).
ft_strnstr - locate a substring in a string (size-bounded).
ft_strncmp - compare strings (size-bounded).
ft_strdup - save a copy of a string (with malloc).
ft_strlcpy - size-bounded string copying.
ft_strlcat - size-bounded string concatenation.

---> Non-standard functions

[ft_itoa](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_itoa.c) - convert integer to ASCII string.                                      
[ft_substr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_substr.c) - extract substring from string.                                    
[ft_strtrim](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strtrim.c) - trim beginning and end of string with the specified characters.  
[strjoin](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strjoin.c) - concatenate two strings into a new string (with malloc).            
[ft_split](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_split.c) - split string, with specified character as delimiter, into an array of strings.                                                                                                                                              
[ft_strmapi](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strmapi.c) - create new string from modifying string with specified function.                                                                                                                                                
[ft_striteri](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_striteri.c) -applies the fonction f to each character of the string passed as argument , and passing it's index as firt argument                                                                                                    
[ft_putchar_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putchar_fd.c) - output a character to given file.                          
[ft_putstr_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putstr_fd.c) - output string to given file.                                
[ft_putendl_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putendl_fd.c) - output string to given file with newline.                  
[ft_putnbr_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putnbr.c) - output integer to given file.                                  

---> Linked list functions ( BONUS PART)

ft_lstnew - create new list.
ft_lstsize - count elements of a list.
ft_lstlast - find last element of list.
ft_lstadd_back - add new element at end of list.
ft_lstadd_front - add new element at beginning of list.
ft_lstdelone - delete element from list.
ft_lstclear - delete sequence of elements of list from a starting point.
ft_lstiter - apply function to content of all list's elements.
ft_lstmap - apply function to content of all list's elements into new list.


