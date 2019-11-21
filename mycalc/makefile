start:
	yacc -dv mycalc.y
	lex mycalc.l
	cc -o mycalc -w  y.tab.c lex.yy.c
	
clean:
	rm -rf mycalc y.tab.c lex.yy.c y.output y.tab.h
