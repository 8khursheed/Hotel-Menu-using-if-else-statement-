#include <stdio.h>
#include <stdlib.h>

int main()
{
    int choice ;

    printf("-- Welcome to the cafe--\n");
    printf("1. Tea\n");
    printf("2. coffee\n");
    printf("3. Burger\n");
    printf("4. Pizza\n");
    printf(" Please enter your choice 1-4\n");


    scanf("%d",&choice);

    if(choice==1){
        printf("Here is your hot Tea");

    }
     else if(choice==2){
        printf("Here is your Coffee ");
     }
     else if(choice==3){
        printf("Here is your Bugger ");
     }
     else if (choice==4){
        printf("Here is your pizza");
     }
     else {
        printf("Invalid choice");
     }


    return 0;
}

