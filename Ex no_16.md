# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1.Start the program.

2.Read three fractional (float) numbers from the user.

3.Use conditional operators to compare the first two numbers, then compare the result with the third.

4.Store the minimum value in a variable.

5.Display the minimum and end the program.

## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.


#include <stdio.h>

int main() {
    float a, b, c, min;

    printf("Enter three fractional numbers: ");
    scanf("%f%f%f", &a, &b, &c);

    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    printf("Minimum value: %.2f\n", min);

    return 0;
}

*/
```

## Output:

<img width="499" height="177" alt="517816150-cae20489-e45b-48da-a4a9-201867a0ea37" src="https://github.com/user-attachments/assets/10ed6410-d5e6-48ef-8dcf-c2548d9f463b" />


## Result:
Thus the program was executed and the output was verified successfully.
