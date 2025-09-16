# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
STEP 1 : Start the program and import the required libraries.

STEP 2 : Seed the random number generator using the current time(i.e) rand(time(0));

STEP 3 : Get the number of randon number to generate.

STEP 4 : Pass the value for number of iterations and print the numbers.

STEP 5 : End the program.

# PROGRAM:
```python
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
 {
    srand(time(0));  
    int random = rand(); 
    printf("Random number: %d\n", random); 
    return 0;
}
```

# OUTPUT:

![Screenshot 2025-03-21 090159](https://github.com/user-attachments/assets/64120105-0cf1-46bf-b5d6-f82d86827302)
# RESULT:
Thus the implementation of Pseudorandom Number Generation Using Standard library is successfully executed.
