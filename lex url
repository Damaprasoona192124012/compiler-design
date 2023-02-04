%{
int c=0;
%}
%%
["https://"]w{3,3}["."][a-z]+".com"|".edu"|".in" {c=1;}
%%
int yywrap(void){}
int main()
{
printf("enter the url : ");
yylex();
if(c==1)
printf("\nvalid............");
else
printf("\ninvalid...........");
}
