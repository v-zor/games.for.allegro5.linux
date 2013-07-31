CXX=g++
CFLAGS=-O

all: main

main:
	$(CXX) -c bmp.c
	$(CXX) -c main.c

	$(CXX) -o main *.o -lalleg

clean:
	rm -f *.o main
