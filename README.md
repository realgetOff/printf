<p align="center">
  <img src="https://github.com/realgetOff/main/blob/main/Header/Black%20Yellow%20Bold%20Bag%20Fashion%20Sale%20Banner%20(2).png">
</p>

<p align="center">
	<img src="https://img.shields.io/badge/status-finished-chocolate"/>
	<img src="https://img.shields.io/badge/evaluated-31%20%2F%2010%20%2F%202024-chocolate"/>
	<img src="https://img.shields.io/badge/score-100%2F100-chocolate"/>
	<img src="https://img.shields.io/badge/language-C_95.8%25-chocolate"/>
	<img src="https://img.shields.io/badge/last_commit-november-chocolate"/>
	<a href='https://profile.intra.42.fr/users/mforest-' target="_blank"><img alt='42' src='https://img.shields.io/badge/Intra-100000?style=flat-round&logo=42&logoColor=white&labelColor=000000&color=000000'/></a>
</p>

<p align="center">
	<a href="#about">About</a> •
	<a href="#how-to-use">How to use</a> •
	<a href="#mandatory">Mandatory</a> •
	<a href="#bonus">Bonus</a> •
	<a href="#norminette">Norminette</a> •
	<a href="#contributing">Contributing</a> •
</p>

## ABOUT
This project involved recreating the well-known C library function, printf. This provided a valuable learning opportunity in variadic arguments and structures, particularly if we intend to incorporate additional flags into our implementation of print.

- [Subject](https://github.com/realgetOff/ft_printf/blob/main/en_ft_printf_subject.pdf) `PDF`
- [References](https://github.com/realgetoff/ft_printf) `GitHub`

## HOW TO USE
#### 1º - Clone the repository
```git
git clone https://github.com/realgetOff/ft_printf.git
```

#### 2º - Enter the project folder and run `make`
```bash
cd ft_printf/ft_printf
make
```

#### 3º - To use in your code, include the header
```c
#include "ft_printf.h"
```

#### MAKEFILE RULES

`make` or `make all` - Compile ft_printf files.

`make clean` - Delete all .o (object files) files.

`make fclean` - Delete all .o (object files) and .a (executable) files.

`make re` - Use rules `fclean` + `all`.

## MANDATORY
> This ft_printf function supports several format specifiers, described below:
- [x] `%c` - Print a single character;
- [x] `%s` - Print a string;
- [x] `%p` - Print void * pointer argument in hexadecimal format;
- [x] `%d` - Print a decimal (base 10) number;
- [x] `%i` - Print an integer in base 10;
- [x] `%u` - Prints an unsigned decimal (base 10) number;
- [x] `%x` - Print a number in hexadecimal (base 16) lowercase format;
- [x] `%X` - Print a number in hexadecimal (base 16) uppercase format;
- [x] `%%` - Print a percentage sign;

## BONUS
- [ ] Manage any combination of the following flags: `-O` and the field minimum width under all conversions;
- [ ] Manage all the following flags: `#` ` ` `+`;

## NORMINETTE
> At 42 School, it is expected that almost every project is written following the Norm, which is the coding standard of the school.

```
- No for, do...while, switch, case, goto, ternary operators, or variable-length arrays allowed;
- Each function must be a maximum of 25 lines, not counting the function's curly brackets;
- Each line must be at most 80 columns wide, with comments included;
- A function can take 4 named parameters maximum;
- No assigns and declarations in the same line (unless static);
- You can't declare more than 5 variables per function;
- ...
```

* [42 Norms](https://github.com/42School/norminette/blob/master/pdf/en.norm.pdf) - Information about 42 code norms. `PDF`
* [Norminette](https://github.com/42School/norminette) - Tool to respect the code norm, made by 42. `GitHub`
* [42 Header](https://github.com/42Paris/42header) - 42 header for Vim. `GitHub`

## CONTRIBUTING

If you find any issues or have suggestions for improvements, feel free to fork the repository and open an issue or submit a pull request.
All credits goes to @jotavare (for the README.md).
