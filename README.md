# C-programming
// program to check whether the entered number is a prime number or not.

#include <stdio.h>
int main()
{
	int i,num,prime=1;
	printf("Enter the value of num:");
	scanf("%d",&num);
	for(i=2;i<num;i++){
		if(num%i==0){
			prime=0;
			break;
		}
	}
    if(prime==0) {
    	printf("It is not a prime number."); //condition for prime number checking...
}
else{
	printf("It is a prime number.");
	}


	return 0;
}
