
CC=gcc
CFLAGS=-I. -Wall -std=c99
DEPS = queue.h
OBJ = queue.o main.o 
BIN = main

INCDIR =../include
ODIR=.

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

$(BIN): $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)

.PHONY: clean

clean:
	rm -f $(ODIR)/*.o *~ core $(INCDIR)/*~ $(OBJ) $(BIN) *.out 
