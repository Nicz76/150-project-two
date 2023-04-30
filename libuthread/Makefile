# Target library
lib := libuthread.a

all: $(lib)
	
	ar rcs libuthread.a

lib: queue.c queue.h
	gcc -02 -Wall -Wextra -Werror -o $@ $^
	
clean:
	rm -f lib
## TODO: Phase 1
