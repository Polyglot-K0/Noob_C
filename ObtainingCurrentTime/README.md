```c
#include <stdio.h>
// time.h header (file) - is requred, compiler might be cross with you
#include <time.h>

int main(){ 

    //time_t is a type - used for representing time
    //is mostly used as an alias for numeric type - typically 'long' or '__int64' (some sytems)
    //its used to hold the number of seconds since a spec ref point in time (also, the epoch)
    //this allows the programmer with time-related data

    // creating a variable named 'now' of type time_t
    // HINT: var name 'now' indicates it stores the current time
    time_t now;
    
    // time() function requires the time_t variable
    time(&now);
    printf("The computer thinks its %lf\n", now);
    printf("%s",ctime(&now));

    return(0);
}
```
