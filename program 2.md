#include <stdio.h> 
 
int main() 
{ 
	int n; 
	printf("Enter the number :\n"); 
	scanf("%d",&n); 
	 
	if(n%5 ==0 && n%11==0) 
	{ 
		printf("%d is divisible by 5 & 11\n",n); 
	} 
	 
	else 
	{ 
		printf("%d is not divisible by 5 & 11",n); 
	} 
	 
return 0; 
} 
