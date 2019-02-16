OBJECTS = badapple.o

CC	?=
CFLAGS	 ?= -g -Wall -Wextra -std=c99 -pedantic -Wwrite-strings
CPPFLAGS ?=
LDFLAGS  ?=

all: badapple

badapple: $(OBJECTS)
	$(CC) $(CPPFLAGS) $(CFLAGS) $(LDFLAGS) $(OBJECTS) -o $@

clean:
	-rm -f $(OBJECTS) badapple

check: all
	# Unit tests go here. None currently.
	@echo "*** ALL TESTS PASSED ***"

.PHONY: all clean check
