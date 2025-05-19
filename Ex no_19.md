# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Start the program.

2.Read an integer and the number of positions to shift.

3.Perform left shift (<<) on the integer by the given positions.

4.Perform right shift (>>) on the integer by the given positions.

5.Display the results and end the program.

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: Nabisha A 
RegisterNumber: 212223060177

#include <stdio.h>

int main() {
    int num, shift;
    int leftShift, rightShift;

    printf("Enter an integer: ");
    scanf("%d", &num);

    printf("Enter number of positions to shift: ");
    scanf("%d", &shift);

    leftShift = num << shift;
    rightShift = num >> shift;

    printf("Result after left shift by %d positions: %d\n", shift, leftShift);
    printf("Result after right shift by %d positions: %d\n", shift, rightShift);

    return 0;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/661ee331-3fac-4c14-9922-8003f824b3e2)

## Result:
Thus the program was executed and the output was verified successfully.
