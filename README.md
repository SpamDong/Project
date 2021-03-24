# Project
#include<stdio.h>

int main()
{
	int num1,num2;
	int i,j,k;


	for(k=0;k<3;k++)
	{
		for(i=1; i<10; i++)
		{
			for(j=1+(k*3); j<4+(k*3); j++)
			{
				printf("%d * %d = %d\t", j,i,i*j);
			}
			printf("\n");
		}
		printf("\n");
	}
	
}
