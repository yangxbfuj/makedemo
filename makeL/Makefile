demo:build/print.o build/main.o
	gcc -o demo build/print.o build/main.o

build/main.o:main.c main.h
	gcc -c -o build/main.o main.c

build/print.o:print.c print.h
	gcc -c -o build/print.o print.c

.PHONY:clean
clean:
	rm -f *.o demo