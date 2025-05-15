# EX 15 C Program to convert lower case vowel letters to upper case letters using the switch statement (EX. a - A, i - I)
## AIM:
To write a C Program to convert lower case vowel letters to upper case letters using the switch statement (EX. a - A, i - I)
## Algorithm
1. Start
2. Declare a character variable c
3. Read a character from the user
4. Use a switch statement on c:  
   a. If ch is 'a', print 'A'  
   b. If ch is 'e', print 'E'  
   c. If ch is 'i', print 'I'    
   d. If ch is 'o', print 'O'  
   e. If ch is 'u', print 'U'  
5. Default: Print "Not a lowercase vowel"
6. End
## Program:
```
#include<stdio.h>
#include<ctype.h>
int main()
{
    char c;
    scanf("%c",&c);
    if(c=='a'||c=='e'||c=='i'||c=='o'||c=='u')
    {
        printf("%c",c-32);
    }
    else
    printf("The Character is not vowel");
}
```

## Output:

![image](https://github.com/user-attachments/assets/2ed3a43b-14ed-47cc-9ee7-7c8e7cc8ceac)


## Result:
Thus the program was executed and the output was verified successfully.
