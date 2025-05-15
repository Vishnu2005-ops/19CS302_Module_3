# EX 13 C program to read n elements as input and print the elements of the array (integer).
## AIM:
To write a C program to read n elements as input and print the elements of the array (integer).
## Algorithm
1. Start
2.  an integer array and variables n, i
3. Read the value of n (number of elements)
4. Loop from i = 0 to n-1:  
   a. Read arr[i]
5. Loop from i = 0 to n-1:  
   b. Print arr[i]
6. End  

## Program:
```
#include <stdio.h>
int main()
{
    int n, i;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
}
    for(i=0;i<n;i=i+1)  
    {
        printf("%d ",a[i]);
}
    return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/0847c5a6-14c9-425f-a5a4-8a8cb9669f88)

## Result:
Thus the program was executed and the output was verified successfully.
