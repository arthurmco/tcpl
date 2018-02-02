# Observations about the errors in the example program, contained in the first chapter
[![asciicast](https://asciinema.org/a/p2OwHVZjrptU9tMy45uskMpw7.png)](https://asciinema.org/a/p2OwHVZjrptU9tMy45uskMpw7)

> GCC complained because we didn't declare previously the functions who were
> used in the code. So we received a lot of warnings, even with the compilation
> exactly equal to the example given. The warnings would appear, don't matter
> how you compiled the code, because in every C language program you need to
> include the headers, like the traditional ones:

```C
#include <stdio.h>
#include <stdlib.h>
```
> In this case below, it would be only the header that include the standard
> functions for input/output in the language. In addition, the compiler warns
> too because we're using only `main`, before we used `main`, but now `int
> main()` is used. Inside these parenthesis we have the arguments passed in the
> code, but in the book example the `()` are empty. The curly brackets `{}`
> wrap the commands inside it, they form the function, but the "curly brackets"
> are more known as the code's body.
>
> Between those brackets are the main functions used in the code. However,
> in languages like Python you don't use `{}` nor `;`, in C things are
> different, if we didn't put the `;`, the compiler would tell us that we didn't
> end the function. In the C language is very important to use `;`, because in
> it this char is like an "end", and the compiler can better understand what
> happened there and proceed to the next likes.

```C
 #include <stdio.h>
 ```
 
> In C any sequence of characters of any number between quotation marks `"..."`
> is called a string, for now our use as an argument for `printf` and other
> functions. The `\n` notation means new line.
