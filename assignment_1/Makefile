CC=gcc
DEPS = average.h
OBJ= average.o	main.o
CFLAGS=-std=c99

%.o: %.c $(DEPS)
	$(CC) $(CFLAGS) -c -o $@ $<

main: $(OBJ)
	$(CC) -o $@ $^ $(CLFAGS) 
