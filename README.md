# Calander-in-c-program
 This C code introduces a program that aids users in exploring days within the month of September. By inputting a date, the program utilizes a switch statement to unveil the corresponding day of the week accurately. Enhancing user interaction, the program furnishes diverse responses for each day, enhancing its user-friendliness.  
This C code is a simple interactive program that helps users explore days of the week within the month of September. It employs user input and a switch statement to provide the day of the week corresponding to a given date. Additionally, the program invites users to inquire about special events in September and tailors responses based on their choices.

Here's how the code works:

Users are prompted to input a date within the month of September.
The program uses a switch statement to match the input date with the correct day of the week. It then prints the day associated with that date.
Users are then asked if they want to know about special events in September.
The user's response is read, and based on their input, the program either displays a list of notable events in September or responds with "okay."
This code effectively demonstrates how to take user input, process it using switch and if statements, and provide customized outputs. It's designed to help users quickly determine the day of the week for a given date in September while also offering information about special events. The code emphasizes user interaction, making it a useful example of combining input processing and dynamic responses in a simple program.
YOU HAVE TO DO CERTAIN CHANGES LIKE CHANGING NAME OF MONTHS AND WEEKS OR ELSE YOU CAN JUST CONNECT ME!
___________________________________________________________________________________________________________________________________________________________________________
                                                                  MAIN CODES STARTS FROM HERE ⬇️
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include<stdio.h>
int main()
{
     int Calander,specialevent,yes,no;
     printf("Please select date from month of September:-");
     scanf("%d",&Calander);

     switch (Calander)

{
     
     case 1:
               printf("Its friday\n");
          break;
     case 2:
               printf("Its saturday\n");
          break;
     case 3:
               printf("Its sunday\n");
          break;
     case 4:
               printf("Its monday\n");
          break;
     case 5:
               printf("Its tuesday\n");
          break;
     case 6:
               printf("Its wednesday\n");
          break;
     case 7:
               printf("Its thursday\n");
          break;
     case 8:
               printf("Its friday\n");
          break;
     case 9:
               printf("Its saturday\n");
          break;
     case 10:
               printf("Its sunday\n");
          break;
     case 11:
               printf("Its monday\n");
          break;
     case 12:
               printf("Its tuesday\n");
          break;
     case 13:
               printf("Its wednesday\n");
          break;
     case 14:
               printf("Its thursday\n");
          break;
     case 15:
               printf("Its friday\n");
          break;
     case 16:
               printf("Its saturday\n");
          break;
     case 17:
               printf("Its sunday\n");
          break;
     case 18:
               printf("Its monday\n");
          break;
     case 19:
               printf("Its tuesday\n");
          break;
     case 20:
                 printf("Its wednesday\n");
          break;
     case 21:
               printf("Its thursday\n");
          break;
     case 22:
               printf("Its friday\n");
          break;
     case 23:
               printf("Its saturday\n");
          break;
     case 24:
               printf("Its sunday\n");
          break;
     case 25:
               printf("Its monday\n");
          break;
     case 26:
               printf("Its tuesday\n");
          break;
     case 27:
               printf("Its wednesday\n");
          break;
     case 28:
               printf("Its thursday\n");
          break;
     case 29:
               printf("it's friday\n");
          break;
     case 30:
               printf("Its saturday\n");
          break;
     default:
          printf("Wrong date selection");
          break;
}


    printf("Do you want to know about special events this month?\n Enter yes/no:\n");
    scanf("%d",&specialevent);


    if(specialevent<=yes)
    {
    printf("6th september 2023:- Janmastami(Smarta)\n 7th september 2023:- Janmastami\n 19th september 2023:- Ganesh Chaturti\n 28th september 2023:- Milad-un-nabi");
    }

    else if(specialevent>=no)
    {
    printf("okay..");
    }






     return 0;

}
