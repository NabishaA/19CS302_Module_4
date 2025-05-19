# EX 18 C program to find frequency of a character in the given input.
## DATE:
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1.Start the program.

2.Read the input string from the user.

3.Read the character whose frequency needs to be found.

4.Traverse the string and count how many times the character appears.

5.Print the frequency and end the program.  

## Program:
```
/*
C program to find frequency of a character in the given input.
Developed by: Nabisha A
RegisterNumber: 212223060177

#include <stdio.h>

int main() {
    char str[1000], ch;
    int i = 0, count = 0;

    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);

    printf("Enter the character to find frequency: ");
    scanf("%c", &ch);

    while(str[i] != '\0') {
        if(str[i] == ch)
            count++;
        i++;
    }

    printf("Frequency of '%c' = %d\n", ch, count);

    return 0;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/adfa6412-c86e-46f1-a7b8-955354e616ea)

## Result:
Thus the program was executed and the output was verified successfully.
