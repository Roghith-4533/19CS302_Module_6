# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
## DATE:
## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1. start
2. declare enum type
3. declare all days ina week
4. print result
5. end

## Program:
```
#include <stdio.h>
enum weekdays {
 Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
};
int main() {
 enum weekdays today = Wednesday;
 if (today == Wednesday) {
 printf("Today is Wednesday.\n");
 }
}
```

## Output:
![WhatsApp Image 2025-05-19 at 15 59 40_d2564985](https://github.com/user-attachments/assets/6ddd6188-3f05-4ba5-b0d1-a1c0aad77b37)




## Result:
Thus the program was executed and the output was verified successfully.
