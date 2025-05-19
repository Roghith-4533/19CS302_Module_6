# EX 30 C program to add two integer elements in an array using realloc() and that array already has three elements.
## DATE:
## AIM:
To write a C program to add two integer elements in an array using realloc() and that array already has three elements.

## Algorithm
1. start
2. declare arrray size
3. initialize array element using malloc()
4. update array size using malloc()
5. print the result
6. end

## Program:
```
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *arr, size, i;
 size = 3;
 arr = (int *)malloc(size * sizeof(int)); 
 for (i = 0; i < size; i++) {
 arr[i] = i * 10; }
 printf("Original array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }
 printf("\n");
 size *= 2;
 arr = (int *)realloc(arr, size * sizeof(int)); 
 for (i = size / 2; i < size; i++) {
 arr[i] = i * 10;
printf("Updated array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }}
```

## Output:
![WhatsApp Image 2025-05-19 at 16 05 10_c043baab](https://github.com/user-attachments/assets/79f37e93-d51b-4af5-9f5f-87031813ae47)


## Result:
Thus the program was executed and the output was verified successfully.
