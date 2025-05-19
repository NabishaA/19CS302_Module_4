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
Developed by: Nabisha A
RegisterNumber: 212223060177

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

![image](https://github.com/user-attachments/assets/36f14071-453a-4d4a-8bc1-3eb8fd730346)


## Result:
Thus the program was executed and the output was verified successfully.
