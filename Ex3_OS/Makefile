
all: clientexe serverexe
	

clientexe: client.o
	gcc -o clientexe client.o

serverexe: server_new.o
	gcc -pthread -o serverexe server_new.o 

client.o: client.c
	gcc -c client.c

server_new.o: server_new.c
	gcc -pthread -c server_new.c 	

.PHONY: clean all

clean:
	rm -f *.o serverexe clientexe