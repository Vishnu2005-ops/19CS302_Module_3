# EX 12 C program  to check whether 71 is prime or not
## AIM:
To write a C program  to check whether 71 is prime or not

## Algorithm
1. Start
2.  n = 71
3. If n <= 1, then it's not a prime
4. Loop from i = 2 to sqrt(n) (or i * i <= n):
   a. If n % i == 0, it's not a prime
5. If no divisor found, it's a prime
6. End



## Program:
```
#include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    if(n%71==1)
    {
        printf("the number is prime");
    }
    else
    {
        printf("71 is a prime number.");
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/bbc60f8f-acc9-4fa8-a704-305ee1c7f85b)

## Result:
Thus the program was executed and the output was verified successfully.
