CC ?= gcc
CFLAGS_common ?= -O0 -Wall -std=gnu99

EXEC = main
all: $(EXEC)

main: main.c
	$(CC) $(CFLAGS_common) -o $@ $@.c

clean:
	$(RM) $(EXEC) *.o perf.*
