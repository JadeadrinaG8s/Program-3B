# Program-3B
C module 3
EX NO-3)B)A C program to print all leap years from 1 to N.
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO write C program to print all leap years from 1 to N.
ALGORITHM:
1)take a limit as input from the user.2)run for loop till the limit 3)check if the number id divisible by 4 .4)print if it is divisible using the printf() function.
PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,i;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        if(i%4==0)
        {
            printf("%d ",i);
        }
    }
}
```
OUTPUT:
<img width="869" height="230" alt="Screenshot 2025-10-19 221216" src="https://github.com/user-attachments/assets/acad6750-b0cd-4252-a1d4-dc0ce540dd37" />
RESULT:
Thus,a  C program to print all leap years from 1 to N has been successfully executed.

