# PALINDROM
PALINDROM
#include <stdio.h>
int main()
{
int a=12,s=0;
int temp=a;
while(a>0)
{
    s=s*10+a%10;
a=a/10;
   }
 if(temp==s)
   {
 printf("PALINDROM");
   }
else
   {
 printf("NOT");
   }
}








