all:
	flex tiny.l
	bison -t -d tiny.y
	g++ lex.yy.c tiny.tab.c -o tiny.out
clear:
	rm -rf tiny.tab.c tiny.tab.h
	rm -rf lex.yy.c
	rm -rf tiny.out