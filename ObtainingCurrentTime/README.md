```c
#include <stdio.h>
// time.h header (file) - is requred, compiler might be cross with you
#include <time.h>

int main(){ 

    // time_t is a type - used for representing time
    // is mostly used as an alias 

    time_t now;
    
    // time() function requires the time_t variable
    time(&now);
    printf("The computer thinks its %lf\n", now);
    printf("%s",ctime(&now));

    return(0);
}
```
