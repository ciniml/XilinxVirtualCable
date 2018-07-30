.PHONY: all clean

all: xvcServer

clean:
	-@rm xvcServer

xvcServer: xvcServer.c
	$(CC) $< -o $@ -O2 
