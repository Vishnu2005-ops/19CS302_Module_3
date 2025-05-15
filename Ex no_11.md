# EX 11 C program to convert a 11010101 binary value to decimal.


## AIM:
To write a C program to convert a 11010101 binary value to decimal.

## Algorithm
1. Start
2. nitialize variables: binary, decimal = 0, base = 1, rem
3. Read the binary number (as an integer or string)
4. Loop while binary is not 0:  
   a. rem = binary % 10 (get the last digit)  
   b. decimal = decimal + rem * base  
   c. base = base * 2  
   d. binary = binary / 10 (remove the last digit)  
5. Print the decimal value
6. End

## Program:
```
#include <stdio.h>
#include<math.h>
int main()
{
    int d=0,a=11010101,r,b;
    b=a;
    int i=0;
    while(a!=0)
    {
        r=a%10;
        a/=10;
        d+=r*pow(2,i);
        i++;
    }
    printf("%d in binary = %d in decimal",b,d);
}
```

## Output:
![image](https://github.com/user-attachments/assets/7ccaceba-4c8d-4ab6-8add-2b426867f814)


## Result:
Thus the program was executed and the output was verified successfully.
