# EX 29 C program to create two float variables using calloc() and find minimum among them.
## DATE:
## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
1. start
2. initialize two variables value of calloc
3. prompt the user to enter values
4. read the values using scanf
5. find minimum and print result
6. end
   

## Program:
```
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
```

## Output:
![WhatsApp Image 2025-05-19 at 16 02 36_80f2fe3f](https://github.com/user-attachments/assets/c869ca02-2351-4218-a77a-85938d473b55)




## Result:
Thus the program was executed and the output was verified successfully.
