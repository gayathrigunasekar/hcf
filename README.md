# hcf
hcf or gcd for two numbers
#include<stdio.h>
int hcf(int,int);
int main()
{int a,b,gcd;
printf("enter two numbers to calculate hcf\n");
scanf("%d%d",&a,&b);
gcd=hcf(a,b);
printf("gcd/hcf is %d",gcd);
getch();}
int hcf(int x,int y )
{if(y!=0)
return hcf(y,x%y);
else
return x;}
