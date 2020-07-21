#include<stdio.h>
 main()
 {
 	printf("Pick a number : \n1. \n2. \n3. \n4. \n5.");
 	int choice=0;
 	scanf("%d",&choice);
 	switch(choice)
 	{
 		case 1:
 			printf(" food item - Burger\n Price - Rs 129");
 			break;
 	    case 2:
 	    	printf(" food item - Pasta\n Price - Rs 179");
 	    	break;
 	    case 3:
 	    	printf(" food item - Pizza\n Price - Rs 239");
 	    	break;
 	    case 4:
 	    	printf(" food item - French Fries\n Price - Rs 99");
 	    	break;
 	    case 5:
 	    	printf(" food item - Sandwich\n Price - Rs 149");
 	    	break;
 	    	default :
 	    		printf("invalid choice");
	 }
 }
