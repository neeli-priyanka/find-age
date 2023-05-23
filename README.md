# find-age
#include<stdio.h>
int main()
{
	int n,i;
	printf("enter n value");
	scanf("%d",&n);
	while(n<=20)
	{
		scanf("%d",&n);
		if(n<10)
		printf("baby age");
		else if(n<=15){
		printf("school age");
		}
		else
		printf("adult age");
	}
}
