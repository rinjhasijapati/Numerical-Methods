#include<stdio.h>

int main()
{
	float x[100],y[100],xp,yp=0,p;
	int i,j,n;
	
	printf("\nEnter number of data: ");
	scanf("%d",&n);
	
	printf("\nEnter data: ");
	for(i=1;i<=n;i++)
	{
		printf("x[%d]= ",i);
		scanf("%f",&x[i]);
		
		printf("y[%d]= ",i);
		scanf("%f",&y[i]);
	}
	
	printf("\nEnter interpolation point: ");
	scanf("%f",&xp);
	
	for(i=1;i<=n;i++)
	{
		p=1;
		
		for(j=1;j<=n;j++)
		{
			if(i!=j)
			{
				p=p*(xp-x[j])/(x[i]-x[j]);
			}
		}
		
			yp=yp+p*y[i];
	}
	
	printf("\nInterpolated Value at %.3f is %.3f.",xp,yp);
	return 0;
}
