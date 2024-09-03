all:	add_numbs

add_numbs:	add_numbs.cpp
	g++	-o	add_numbs	add_numbs.cpp

dump:	add_numbs
	objdump	-d	add_numbs.exe	>	add_numbs.asm

clean:
	rm	-f	add_numbs	add_numbs.asm
	
run:	add_numbs
	.\add_numbs