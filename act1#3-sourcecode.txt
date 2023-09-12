#include<stdio.h>

main()
{
	//variable
	int amt=0;
	
	//input
	printf("Input an amount: ");
	scanf("%d",&amt);
	
	//process and output
	printf("\n1000=%d",amt/1000);
	printf("\n500=%d",amt%1000/500);
	printf("\n200=%d",amt%1000%500/200);
	printf("\n100=%d",amt%1000%500%200/100);
	printf("\n50=%d",amt%1000%500%200%100/50);
	printf("\n20=%d",amt%1000%500%200%100%50/20);
	printf("\n10=%d",amt%1000%500%200%100%50%20/10);
	printf("\n5=%d",amt%1000%500%200%100%50%20%10/5);
	printf("\n1=%d",amt%1000%500%200%100%50%20%10%5/1);
}