#include <stdlib.h>
#include <stdio.h>

int main()
{ 
	float arrayOfCoefficient[100],sumOfPolynomial=0,XValue; 
	int n,i; 
	
	printf("Highest degree of a polynomial's to solve the value:"); 
	scanf("%d",&n); 
	
	printf("Each coefficients of polynomial one by one:"); 
	for(i=n;i>=0;i--) 
	{
		scanf("%f",&arrayOfCoefficient[i]);
	} 
	
	printf("Enter the value of xValue of polynomail :"); 
	scanf("%f",&XValue); 
	for(i=n;i>0;i--) 
	{
		sumOfPolynomial=(sumOfPolynomial+arrayOfCoefficient[i])*XValue;
	} 
	
	sumOfPolynomial=sumOfPolynomial+arrayOfCoefficient[0]; 
	
	printf("nEvaluted Value of hole expression is =%f",sumOfPolynomial); 
	return 0;
}
