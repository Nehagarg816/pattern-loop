# pattern-loop
This is a program to print required pattern using nested loop.
#include<stdio.h>
#include<conio.h>
void main()
{
	int i,j,a,b;
	for(b=1;b<=5;b++)
	{
	printf("%d ",b);
	printf("Enter one number a:");
	scanf("%d",&a);
	for(i=1;i<=a;i++)
	{
		for(j=1;j<=i;j++)
		{
		printf("*");
	    }
	    printf("\n");
	}
    }
}
