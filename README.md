# c-1
program to add 2 numbers
#include<stdio.h>
#include<string.h>
int main()
{
char str1[100],str2[100];
printf("enter the string1:");
scanf("%s", str1);
printf("enter the string2:");
scanf("%s", str2);
strcat(str1, str2);
printf("concatenated string =%s\n",str1);
return 0;
}
