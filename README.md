# LibftASM
Simple library of assembly functions for MacOS 64bit assembly using Intel syntax

## Functions
	void ft_bzero(void *sl, size_t n);
	int ft_isalpha(int c);
	int ft_isupper(int c);
	int ft_islower(int c);
	int ft_isdigit(int c);
	int ft_isalnum(int c);
	int ft_isascii(int c);
	int ft_isprint(int c);
	int ft_toupper(int c);
	int ft_tolower(int c);
	size_t ft_strlen(const char *s);
	int ft_puts(const char *s);
	void *ft_memset(void *b, int c, size_t len);
	void *ft_memcpy(void *restrict dst, const void *retrict, size_t n);
	char *ft_strdup(const char *s1);
	void ft_cat(int fd);	

## Useful links and resources:
- Intel instruction set reference http://faydoc.tripod.com/cpu/
- x64 Cheat sheet https://cs.brown.edu/courses/cs033/docs/guides/x64_cheatsheet.pdf
- Assembly conditions https://www.tutorialspoint.com/assembly_programming/assembly_conditions.htm
- System calls https://syscalls.kernelgrok.com/
- understanding stack frame https://idea.popcount.org/2013-07-16-baby-steps-in-x86-assembly/ 
