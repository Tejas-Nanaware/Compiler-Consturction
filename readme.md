This repo contains all the lex and yacc programs that I have learnt in Sem VI in the subject System Programming and Compiler Construction.

All the programs are to be run on Linux Platform.

> Kindly install flex and bison.


For LEX programs,  
```
lex "filename".l  
cc lex.yy.c -ll  
./a.out
```  
  
For LEX & YACC programs together,  
```
lex "filename".l  
yacc "filename".y  
cc lex.yy.c y.tab.h -ll  
./a.out
```
