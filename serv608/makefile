all: server client

server: server.o
	gcc -o server server.o

client: client.o
	gcc -o client client.o
pipe: pipe.o 
	gcc -o pipe pipe.o
clean: 
	rm -f *.o
real_clean: clean
	rm -f sever
	rm -f client
	rm -f pipe
