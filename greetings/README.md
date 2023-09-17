
```C 
#include <stdio.h>

int main(int argc, char *argv[])
{
    // The argument count is always 1 for the progam name
    // if(argc>0) - we would get our handsome devil output
    if(argc<2)
        puts("Hello, you handsome beast!");
    else
        printf("Hello, %s!\n", argv[1]);

        return (0);
}
```

