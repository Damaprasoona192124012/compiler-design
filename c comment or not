#include<stdio.h>
#include<string.h>
int main()
{
     char com [30];
     int i=2,a=0;
     printf("Enter Text : ");
     gets(com);
     if(com[0]=='/')
     {
       if(com[1]=='/')
	   printf("It is a Comment line.");
       else if(com [1]=='*')
       {
          for(i=2;i<=30;i++)
          {
             if(com[i]=='*'&&com[i+1]=='/')
             {
                printf("\n It is a Comment line.");
                a=1;
                break;
              }
              else continue;
           }
          if(a==0)
		  printf("\n It is Not a Comment line.");
        }
       else
       printf("\n It is Not a Comment line.");

     }
     else
     printf("\n It is Not a Comment line.");
     return 0;

}
