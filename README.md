# add-by-functions-
#include<stdio.h>
#include<conio.h>
int main()
{ int x,y;
  sum(x,y);
}
int sum(int,int);
int sum(x,y)
{
    int z;
    printf("enter the values to add");
    scanf("%d%d",&x,&y);
    z=x+y;
    printf("the value of z is %d",z);
}
