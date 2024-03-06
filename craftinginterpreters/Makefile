CC = gcc
CFLAGS = -Wall -Wextra -pedantic -std=c11

SRC = main.c chunk.c memory.c debug.c value.c vm.c scanner.c compiler.c
HEADERS = common.h chunk.h memory.h debug.h value.h vm.h scanner.h compiler.h
EXECUTABLE = main

$(EXECUTABLE): $(SRC) $(HEADERS)
	$(CC) $(CFLAGS) $(SRC) -o $(EXECUTABLE)

.PHONY: clean

clean:
	rm -f $(EXECUTABLE)
