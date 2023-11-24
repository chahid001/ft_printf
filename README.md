
# ft_printf

This project tasks you with reimplementing the printf() function in C, creating ft_printf(). It's an opportunity to explore variadic functions and improve programming skills. Adherence to Norm, memory management, and avoiding unexpected errors are critical.

The mandatory part requires creating a library, libftprintf.a, with ft_printf() handling conversions like characters, strings, pointers, integers, and more. The buffer management of the original printf() is excluded.




## Format Specifiers Reference
- `%c`: Prints a single character.
- `%s`: Prints a string (as defined by the common C convention).
- `%p`: Prints a void * pointer argument in hexadecimal format.
- `%d`: Prints a decimal (base 10) number.
- `%i`: Prints an integer in base 10.
- `%u`: Prints an unsigned decimal (base 10) number.
- `%x`: Prints a number in hexadecimal (base 16) lowercase format.
- `%X`: Prints a number in hexadecimal (base 16) uppercase format.
- `%%`: Prints a percent sign.

## Demo

### create a main

#### Example of main.c

```bash
#include "ft_printf.h"

int main() {
    ft_printf("Hello %d\n", 5);
}
```
#### Deployement

```bash
$> make
ft_Printf HAS BEEN COMPILED SUCCESSFULLY

$> gcc main.c libftprintf.a
$> ./a.out
Hello 5

$>

```



