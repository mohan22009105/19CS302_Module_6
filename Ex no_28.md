# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm

Start.

Declare enum type

Declare all days in a week

Print result

End

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

<img width="465" height="198" alt="image" src="https://github.com/user-attachments/assets/952dba98-ffb4-4f38-bf95-1498ad5c686c" />




## Result:
Thus the program was executed and the output was verified successfully.
