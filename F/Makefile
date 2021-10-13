cc=g++

CFLAGS=.c -Wall
all: hello
hello: main.o function1.o function2.o
	$(cc) main.o function1.o function2.o -o hello
	
main.o: main.cpp
	$(cc) $(CFLAGS) main.cpp
	
function1.o: function1.cpp
	$(cc) $(CFLAGS) function1.cpp
function2.o: function2.cpp
	$(cc) $(CFLAGS) function2.cpp
	
clear:
	rm -rf *o hello
