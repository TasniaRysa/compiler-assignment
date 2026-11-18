
the lexer: ID.l
the parser: ID.py

to run, install  mingw, flex (and python if u dont have it) and run these command in powershell:



flex ID.l
gcc lex.yy.c -o lexer.exe
.\lexer.exe test.c
python ID.py
