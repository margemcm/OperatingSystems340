CC=gcc
CFLAGS=-c -O2 -Wall -g

all: hw4

hw4: dpsim.o hw4.o
	$(CC) dpsim.o hw4.o -o hw4 -lpthread

dpsim.o: dpsim.c
	$(CC) $(CFLAGS) dpsim.c

hw4.o: hw4.c
	$(CC) $(CFLAGS) hw4.c

clean:
	/bin/rm -f hw4 *.o *.gz

run:
	./hw4

tarball:
	# put your tar command here
	tar -cvzf marshall.tar.gz *

