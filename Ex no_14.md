# EX 14 C Program to Print the sum of an Array

## AIM:
To write a C Program to Print the sum of an Array
## Algorithm
1. Start
2. Declare variables: n, i, sum = 0, and arr[]
3. Read the number of elements n
4. Loop from i = 0 to n - 1:  
   a. Read arr[i]  
5. Loop from i = 0 to n - 1:  
   a. Add arr[i] to sum  
6. Print sum
7. End
## Program:
```
#include<stdio.h>
int main()
{
     int sum=0,i;
    int a[7];
    for(i=0;i<7;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=0;i<7;i++)
    {
        sum= sum+a[i];
    }
        printf("Total Sum: %d",sum);
}

```

## Output:

![image](https://github.com/user-attachments/assets/e950cb0a-f8c7-4e70-8c0e-0652b6cb6aff)


## Result:
Thus the program was executed and the output was verified successfully.
