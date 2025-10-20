CC = gcc
TARGET = program
OBJECTS = main.o src1.o src2.o src3.o


all: $(TARGET)

$(TARGET): $(OBJECTS)
	$(CC) $(OBJECTS) -o $(TARGET)
	
main.o : main.c sum.h
	$(CC) -c -o $@ $<

include make1.mk
include make2.mk
include make3.mk

clean:
	rm -f $(OBJECTS) $(TARGET)
	
.PHONY: all clean
