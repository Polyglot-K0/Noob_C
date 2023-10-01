```c
#include <stdio.h>
// time.h header (file) - is requred, compiler might be cross with you
#include <time.h>

int main(){ 

    time_t now;

    time(&now);
    printf("The computer thinks its %lf\n", now);
    printf("%s",ctime(&now));

    return(0);
}
```
