RDIR=..
CC=gcc
INCLUDE=-I$(RDIR)/include
DEFINES=
OPTIONS=-O2 -pedantic
AR=ar
AR_OPTIONS=rcvs
ARLIB=libdriver.a
ARCHIVE=$(RDIR)/libdriver/$(ARLIB)
COMPILE=$(CC) $(DEFINES) $(OPTIONS) -std=c99
SOURCES=add.c \
sub.c

OBJECTS=add.o \
sub.o

$(ARCHIVE): $(OBJECTS)
	$(AR) $(AR_OPTIONS) $(ARCHIVE)$?

%.o: %.c
	$(COMPILE) $(INCLUDE) -c -o $@ $<

clean:
	rm -f $(OBJECTS)
