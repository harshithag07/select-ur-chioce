#include<stdio.h>
main()
{
	//display the no.
	printf("select the no.: \n1. 1\n2. 0");
	int (choice);
	scanf("%d",&choice);
	//select the no.
	switch(choice)
	{
	
	
	case 1:
		printf("it is 1");
		break;
	case 2:
	    printf("it is 0");
		break;
	default :
		printf("invalid");	 
	
}
}
