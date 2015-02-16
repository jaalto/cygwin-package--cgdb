all: test
	# To check curses debugger interface, run
	@echo ../../.build/build/cgdb/cgdb test.exe

test: test.c
	gcc -g -o $@ test.c

clean:
	rm -f *.exe
