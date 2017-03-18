CC=gcc
CFLAGS=-Wall
DEPS=myinclude.h
OBJ = add.o sub.o main.o

%.o: %.c $(DEPS)
	$(CC) $(CFLAGS) -c -o $@ $<

main: $(OBJ)
	gcc $(CFLAGS) -o $@ $^
clean:
	rm -f *.o main.exe