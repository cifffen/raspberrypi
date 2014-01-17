CC=gcc
CFLAGS=-I.
DEPS = helloworld.h funk.h

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

run: helloworld.o funk.o
	gcc -o run helloworld.o funk.o -I.
