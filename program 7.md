#include<stdio.h>
int main()
{

	int n,reverse=0,riminder;
printf("enter the num:");
scanf("%d",&n)	;
while (n!=0)
{
	riminder =( "n % 10");
	reverse=reverse*10+reminder ;
	n/=10;
	
}
printf("reversed num=%d",reverse);
	
	return 0
}
