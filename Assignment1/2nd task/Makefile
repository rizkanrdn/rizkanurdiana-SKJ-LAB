all:	mpy_numbs

mpy_numbs:	mpy_numbs.cpp
	g++	-o	mpy_numbs	mpy_numbs.cpp

dump:	mpy_numbs
	objdump	-d	mpy_numbs.exe	>	mpy_numbs.asm

clean:
	rm	-f	mpy_numbs	mpy_numbs.asm
	
run:	mpy_numbs
	.\mpy_numbs