#include<stdio.h>
int main()
{
		int a1,a2,a3,n,i;
	while(scanf("%d",&n),n!=0)
	{
	if(n==1)
	printf("1\n");
	else if(n==2)
	printf("2\n");
	else
	{
	a1=1,a2=2;
	for(i=3;i<=n;i++)
	{ 
	  a3=a1+a2;
	  a1=a2;
	  a2=a3;
	}
	printf("%d\n",a3);
	}
	}
	return 0;}

