# swapping-of-two-numbers
Swapping of two numbers
#include<stdio.h>
int main()
{
	int a=66,b=70;
	printf("before swaping a=%d b=%d",a,b);
	a=a+b;
	b=a-b;
	a=a-b;
	printf("\n after swapping a=%d b=%d",a,b);
	return 0;
}
