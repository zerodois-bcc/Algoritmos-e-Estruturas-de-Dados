all:
	gcc $(wildcard *.c *.h) -o teste -std=c89 -lm -Wall -Werror -ansi -g
gdb:
	gdb ./teste -tui
val:
	valgrind ./teste -v --leak-check=full
run:
	./teste
