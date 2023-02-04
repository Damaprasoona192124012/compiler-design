//Lex Program: (html.l)//


%{
int tags; 
%}
%%
"<"[^>]*> { tags++; printf("%s \n", yytext); } 
.|\n { } 
%%
int yywrap(void) { 
return 1; } 
int main(void) 
{ 
FILE *f; 
char file[10]; 
printf("Enter File Name : "); 
scanf("%s",file); 
f = fopen(file,"r"); 
yyin = f;
yylex(); 
printf("\n Number of html tags: %d",tags); 
fclose(yyin); 
} 





//Input Source Program: (sample.html) //
<html> 
<body> 
Dept. of CSE, MITS Page 26 
<h1>My First Heading</h1> 
<p>My first paragraph.</p> 
</body> 
</html>
