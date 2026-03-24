# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1.Start the program. 2.Read the input string from the user. 3.Traverse each character of the string until the null terminator is reached. 4.If the character is uppercase (between 'A' and 'Z'), convert it to lowercase by adding 32. 5.Print the converted string and end the program.

## Program:
```
/*
C program to convert the given string to lowercase without using string functions.


#include <stdio.h>

int main() {
    char str[1000];
    int i = 0;

    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);

    while(str[i] != '\0') {
        if(str[i] >= 'A' && str[i] <= 'Z') {
            str[i] = str[i] + 32;  // Convert uppercase to lowercase
        }
        i++;
    }

    printf("Lowercase string: %s", str);

    return 0;
}
```

## Output:
<img width="384" height="161" alt="445559874-dff8eac2-ba53-4c41-97fa-eb368d8e59eb" src="https://github.com/user-attachments/assets/3c7847ea-9a48-4458-9b27-982f72a42070" />



## Result:
Thus the program was executed and the output was verified successfully.
