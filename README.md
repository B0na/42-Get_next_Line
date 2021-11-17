<div align="center">
	<a href="https://www.42sp.org.br/">
		<img src="https://static.wixstatic.com/media/1b540d_3141ceec765a45f4954e1e725e536a72~mv2.png/v1/fill/w_148,h_50,al_c,q_85,usm_0.66_1.00_0.01/42sp_logo_preto.webp">
	</a>
</div>

<h1 align="center"> Get_next_Line </h1>
<h1 align="center">
<p align="center">The aim of this project is to make you code a function that returns a line, read from a file descriptor.</p>



<h2 align="center">
	Project develop for 42Cursus </a>
</h2>

<p align="center">
  	<a href="https://www.linkedin.com/in/eduardo-bonamico-viana-2b23b721b/">
    	<img alt="Linkedin" src="https://img.shields.io/badge/Eduardo Bonamico Viana-blue?style=flat&logo=Linkedin&logoColor=white" />
  	</a>

	
## 🎯 Goal
This project will not only allow you to add a very convenient function to your collection,
but it will also allow you to learn a highly interesting new concept in C programming:
static variables
	
### 👨🏻‍💻 Prototype
```c
char *get_next_line(int fd);
```
	
## 💻 Functions
- [`get_next_line.c`](Mandatory/get_next_line.c) - read the file descriptor.
- [`get_next_line_utils.c`](Mandatory/get_next_line_utils.c) - complementary functions for GNL. (functions were made in the first project - libft)
- [`get_next_line_bonus.c`](Bonus/get_next_line_bonus.c) - read file descriptors.
- [`get_next_line_utils_bonus.c`](Bonus/get_next_line_utils_bonus.c) - complementary functions for GNL. (functions were made in the first project - libft)
	
## Libft helper functions
- [`ft_strdup`](Mandatory/get_next_line_utils.c) - creates a duplicate for the string passed as a parameter.
- [`ft_strjoin`](Mandatory/get_next_line_utils.c) - concatenates two strings.
- [`ft_strlcpy`](Mandatory/get_next_line_utils.c) - copy string to a specific size.
- [`ft_strlen`](Mandatory/get_next_line_utils.c) - calculate the length of a string.
- [`ft_strchr`](Mandatory/get_next_line_utils.c) - locate character in a string.

## ⭐ Bonus Part
get_next_line_bonus makes it possible to manage multiple file descriptors.
