# Quiz-game
#include<stdio.h>
#include<stdlib.h>
void main()
{
    
    int i;
    int ans1,ans2,ans3,ans4,ans5;
    int point1,point01;
    printf("  Welcome to game:\n\n");
    label:
    printf("> Press 1 to start the game\n");
    printf("> Press 0 to exit the game\n");
    scanf("%d",&i);
    if(i==1)
    {
        printf("\nGame has started\n");
    }
    else if (i==0)
    {
        printf("Game has ended\n\n");
        exit(0);
    }
    else
    {
        printf("Invalid Input!!\n\n");
        goto label;

    }
    if(i==1)
    {
        printf("1) How are String represented in memory in C?\n\n");
        printf("1) An array of character.\n");
        printf("2) An object of some class.\n");
        printf("3) Same as other primitive data types.\n");
        printf("4) LinkedList of character.\n");

        printf("Enter your answer:");
        scanf("%d",&ans1);
        if(ans1==1)
        {
            printf("Correct Answer\n");
            point1=5;
            printf("You have scored %d points\n",point1);

        }
        else
        {
             printf("Wrong Answer\n");
            point1=0;
            printf("You have scored %d points\n",point1);
        }
        printf("1) Which of the following is the proper syntax for declaring macros in C?\n\n");
        printf("1) #define long long ||\n");
        printf("2) #define || long long\n");
        printf("3) #define ||\n");
        printf("4) #define long long \n");

        printf("Enter your answer:");
        scanf("%d",&ans2);
        if(ans2==2)
        {
            printf("Correct Answer\n");
            point1+=5;
            printf("You have scored %d points\n",point1);

        }
        else
        {
             printf("Wrong Answer\n");
            point1+=0;
            printf("You have scored %d points\n",point1);
        }
        printf("1) How to declare a double-pointer in C?\n\n");
        printf("1) int *&val\n");
        printf("2) int &val\n");
        printf("3) int *val\n");
        printf("4) int **val\n");

        printf("Enter your answer:");
        scanf("%d",&ans3);
        if(ans3==4)
        {
            printf("Correct Answer\n");
            point1+=5;
            printf("You have scored %d points\n",point1);

        }
        else
        {
             printf("Wrong Answer\n");
            point1+=0;
            printf("You have scored %d points\n",point1);
        }
        printf("1) If p is an integer pointer with a value 1000, then what will the value of p + 5 be?\n\n");
        printf("1) 1020\n");
        printf("2) 1004\n");
        printf("3) 1005\n");
        printf("4) 1010\n");

        printf("Enter your answer:");
        scanf("%d",&ans4);
        if(ans4==1)
        {
            printf("Correct Answer\n");
            point1+=5;
            printf("You have scored %d points\n",point1);

        }
        else
        {
             printf("Wrong Answer\n");
            point1+=0;
            printf("You have scored %d points\n",point1);
            point01=point1;
        }
        
        printf("\nTotal points scored %d out of 20\n",point01);
        







    }
    }.
