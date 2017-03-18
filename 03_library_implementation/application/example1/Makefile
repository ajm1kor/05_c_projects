RDIR=../..
CC=gcc
INCLUDEDIR=-I $(RDIR)/include
LIBDIR=-L $(RDIR)/libdriver
LIBS=-ldriver
OPTIONS=-O2
all:
	$(CC) -o main main.c $(OPTIONS) $(LIBDIR) $(INCLUDEDIR) $(LIBS)
clean:
	rm -f main.exe