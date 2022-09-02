# greatestnumber
#include <stdio.h>
int main() {
    int maxnum;
    int num1,num2,num3 ;
    printf("***************** WELCOME TO THE PROGRAM TO FIND GREATEST NUMBER AMONG THE ENTERED 3 NUMBERS ***********************");
    printf("\n");
    printf("Please Enter 1st Number: ");
    scanf(" %d/n ",&num1);
    printf("Please Enter 2nd Number: ");
    scanf(" %d/n ",&num2);
    printf("Please Enter 3rd Number: ");
    scanf("%d/n ",&num3);

    maxnum = num1;

    if(num2>maxnum)
    maxnum=num2;

    if(num3>maxnum)
    maxnum=num3;

    printf("Largest number is : %d",maxnum);
    printf("\n");
    printf("******************* Program Ends Here , ThankYou ******************");
return 0;
}

