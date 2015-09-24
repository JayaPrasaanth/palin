#include<stdio.h>
#include<string.h>
void main()
{
  char a[10],b[10];
  int c;
  printf("Enter the string");
  scanf("%s",a);
  strcpy(b,a);
  strrev(b);
  c=strcmp(a,b);
  if(c==0)
   {
     printf("The entered string is a palindrome");
   }
  else
   {
    printf("The entered string is not a palindrome");
   }
}
