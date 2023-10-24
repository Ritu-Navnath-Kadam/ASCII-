# ASCII-
#include<stdio.h>
void main()
{
char ch;
printf("enter a character :-");
scanf("%c",&ch);
printf("\nThe ASCII value of '%c' is %d",ch,ch);
printf("\nIts previous character is  '%c' with ASCII value %d",ch-1,ch-1);
printf("\nIts next character is '%c' with ASCII value %d",ch+1,ch+1);
}
