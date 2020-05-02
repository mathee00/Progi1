# 1st Sem Mid Exam
This is a program for an online book store. 
Customers can buy past paper bundles online

Mid semester exam (2020/April) IP

//Supun Suriyaarachchi
// IT20187514

#include<stdio.h>                                               //Include a header file
int main()							//Function main begins program execution
{
	char sCode, ch = 'Y';                                   //Initializing and declaring variables
	int  sCharge = 0, count = 0, numB = 0, Total = 0;	//Initializing and declaring variables
	int  gCode, amount = 0, totAmount = 0, totBill = 0;	//Initializing and declaring variables

	while((count < 5) && (ch == 'Y' || ch == 'y'))		//loop 5 times and also if (ch = 'Y'/'y') 
	{
	  printf(" \n-----------------------------------");
	  printf(" \nEnter subject code:");			//prompt
	  scanf(" %c", &sCode);					//read subject code from the user

	  if (sCode == 'M' || sCode == 'm')
	     {
              printf("You have chosen Mathematics\n");          //Display message
              printf(" \nEnter grade:");			//prompt
	      scanf(" %d", &gCode);				//read grade from the user
	
			if (gCode == 9)
				{		                      
			 	printf(" \nEnter number of past paper bundles needed:");
				scanf(" %d", &numB);
				amount = numB * 3000.0;
				}
			else if (gCode == 10)
			        {
				 printf(" \nEnter number of past paper bundles needed:");
				 scanf(" %d", &numB);
				 amount = numB * 3500.0;
				}
			     else if(gCode == 11)
				{
				 printf(" \nEnter number of past paper bundles needed:");
				 scanf(" %d", &numB);
				 amount = numB * 3500.0;
				}			    
				  else
                                {
				 printf("\nInvalid grade\n");
				 printf("Please try again\n");
				 count--;
				 amount =0;
				}	//End if                      
             }  //End if        
                         
          else if (sCode == 'S' || sCode == 's')
		    {
		     printf("You have chosen Science\n");
		     printf(" \nEnter grade:");
		     scanf(" %d", &gCode);
	
			if (gCode == 9)
				{		                      
			 	printf(" \nEnter number of past paper bundles needed:");
				scanf(" %d", &numB);
				amount = numB * 3000.0;
				}
			else if (gCode == 10)
			        {
				 printf(" \nEnter number of past paper bundles needed:");
				 scanf(" %d", &numB);
				 amount = numB * 3500.0;
				}
			     else if(gCode == 11)
				{
				 printf(" \nEnter number of past paper bundles needed:");
				 scanf(" %d", &numB);
				 amount = numB * 3500.0;
				}			    
				  else
                                {
				 printf("\nInvalid grade\n");
				 printf("Please try again\n");
				 count--;
				 amount =0;
				}	                      
		    }
		 else if (sCode == 'E' || sCode == 'e')
		        {
		         printf("You have chosen English\n");
		         printf(" \nEnter grade:");
		         scanf(" %d", &gCode);
	 
			  if (gCode == 9)
				{		                      
			 	printf(" \nEnter number of past paper bundles needed:");
				scanf(" %d", &numB);
				amount = numB * 3000.0;
				}
			  else if (gCode == 10)
			        {
				 printf(" \nEnter number of past paper bundles needed:");
				 scanf(" %d", &numB);
				 amount = numB * 3500.0;
				}
			       else if(gCode == 11)
				{
				 printf(" \nEnter number of past paper bundles needed:");
				 scanf(" %d", &numB);
				 amount = numB * 3500.0;
				}			    
				    else
                                {
				 printf("\nInvalid grade\n");
				 printf("Please try again\n");
				 count--;
				 amount =0;
				}	                      
		        }

                       else if (sCode == 'H' || sCode == 'h')
		          {
		           printf("You have chosen History\n");
		           printf(" \nEnter grade:");
		           scanf(" %d", &gCode);
	
			                if (gCode == 9)
				          {		                      
			 	           printf(" \nEnter number of past paper bundles needed:");
				           scanf(" %d", &numB);
				           amount = numB * 2500.0;
				          }
			                else if (gCode == 10)
			                  {
				           printf(" \nEnter number of past paper bundles needed:");
				           scanf(" %d", &numB);
				           amount = numB * 3000.0;
				          }
			                     else if(gCode == 11)
				          {
				           printf(" \nEnter number of past paper bundles needed:");
				           scanf(" %d", &numB);
				           amount = numB * 3000.0;
				          }			    
				                  else
                                          {
				           printf("\nInvalid grade\n");
				           printf("Please try again\n");
				           count--;
				           amount =0;
				          }	                      
		           }
			
			      else if (sCode == 'G' || sCode == 'g')
		             {
		              printf("You have chosen Geography\n");
		              printf(" \nEnter grade:");
		              scanf(" %d", &gCode);
	
			                   if (gCode == 9)
				            {		                      
			 	             printf(" \nEnter number of past paper bundles needed:");
				             scanf(" %d", &numB);
				             amount = numB * 2000.0;
				            }
			                   else if (gCode == 10)
			                    {
				             printf(" \nEnter number of past paper bundles needed:");
				             scanf(" %d", &numB);
				             amount = numB * 2500.0;
				            }
			                        else if(gCode == 11)
				            {
				             printf(" \nEnter number of past paper bundles needed:");
				             scanf(" %d", &numB);
				             amount = numB * 2500.0;
				            }			    
				                     else
                                            {
				             printf("\nInvalid grade\n");
				             printf("Please try again\n");
				             count--;
				             amount =0;
				            }	                      
		             }    
				   else if (sCode == 'L' || sCode == 'l')
		                {
		                 printf("You have chosen English literature\n");
		                 printf(" \nEnter grade:");
		                 scanf(" %d", &gCode);

	                                      if (gCode == 10)
			                       {
				                printf(" \nEnter number of past paper bundles needed:");
				                scanf(" %d", &numB);
				                amount = numB * 3000.0;
				               }
			                        else if(gCode == 11)
				               {
				                printf(" \nEnter number of past paper bundles needed:");
				                scanf(" %d", &numB);
				                amount = numB * 3000.0;
				               }			    
				                     else
                                               {
				                printf("\nInvalid grade\n");
				                printf("Please try again\n");
				                count--;
				                amount =0;
				               }	                      
		                }       
					 else if (sCode == 'B' || sCode == 'b')
		                  {
		                   printf("You have chosen Business studies\n");
		                   printf(" \nEnter grade:");
		                   scanf(" %d", &gCode);

	                                         if (gCode == 10)
			                          {
				                   printf(" \nEnter number of past paper bundles needed:");
				                   scanf(" %d", &numB);
				                   amount = numB * 3000.0;
				                  }
			                         else if(gCode == 11)
				                  {
				                   printf(" \nEnter number of past paper bundles needed:");
				                   scanf(" %d", &numB);
				                   amount = numB * 3000.0;
				                  }			    
				                      else
                                                  {
				                   printf("\nInvalid grade\n");
				                   printf("Please try again\n");
				                   count--;
				                   amount =0;
				                  }	                      
		                   }        

			                      else if (sCode == 'I' || sCode == 'i')
		                     {
		                      printf("You have chosen Information and Communication technology\n");
		                      printf(" \nEnter grade:");
		                      scanf(" %d", &gCode);

	                                                if (gCode == 10)
			                                {
				                         printf(" \nEnter number of past paper bundles needed:");
				                         scanf(" %d", &numB);
				                         amount = numB * 3000.0;
				                        }
			                                else if(gCode == 11)
				                        {
				                         printf(" \nEnter number of past paper bundles needed:");
				                         scanf(" %d", &numB);
				                         amount = numB * 3000.0;
				                        }			    
				                             else
                                                        {
				                         printf("\nInvalid grade\n");
				                         printf("Please try again\n");
				                         count--;
				                         amount =0;
				                        }	                      
		                     }  //End else if 

	                                            else
		                         {
		                          printf("\nInvalid subject code\n");
		                          printf("Please try again\n");
		                          count--;	
		                          amount =0;	   
		                         } //End else
	 
	count++;

	if (count == 5) 
        	 {	
		printf("\nYou have entered the maximum number of orders\n");
		totAmount = totAmount + amount;
		break;
        	 }        //End if
	else
		 {
		 printf("\nDo you want more past paper bundles (Y/N)?\n");
                 scanf("%*c%c", &ch);
		 }        //End else

	totAmount = totAmount + amount;                    //Calculate totAmount

	}   //End while
	printf("\n-----------------------------------\n");
         
	totBill = totBill + totAmount;                    //Calculate totBill
	sCharge = totBill * 10 / 100;			  //Calculate sCharge (service charge)
	Total = totBill + sCharge;			  //Calculate Total

	printf(" Order has been placed successfully\n");
	printf(" Your delivery is on the way\n");
	printf(" Thank you for choosing 'Wisdom'\n");
        printf("\n");                                      //line spacing
	printf(" Sub total = Rs.%.2d\n", totBill);         //Displaying the sub total
	printf(" Service charge = Rs.%.2d\n", sCharge);	   //Displaying service charge
	printf("\n");
	printf(" Total Amount= Rs.%.2d\n", Total);	   //Displaying the total amount 
	
	return 0;
}   //End of main function

	
