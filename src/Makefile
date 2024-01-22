CC = gcc
CFLAGS = -Wall

SRCS = $(wildcard *.c)

EXES = $(SRCS:.c=)

all: $(EXES)

%: %.c
	$(CC) $(CFLAGS) -o $@ $<

clean:
	rm -f $(EXES)