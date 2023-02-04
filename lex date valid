%{
#include<stdio.h>
int valid=0;
%}
%%
([0-2][0-9]|3[0-1])\/(0[1-9]|1[0-2])\/([1-2][0-9][0-9][0-9]) {valid=1;}
%%
int main()
{
yyin=fopen("input.txt","r");
yylex();
if(valid==1) printf("It is a valid date\n");
else printf("It is not a valid date\n");
}
int yywrap()
{
return 1;
}



//input text file//
16/01/2003
