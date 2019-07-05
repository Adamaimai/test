helloworld:hello.o 1.o
	gcc hello.o 1.o -o helloworld

hello.o:hello.c wr.h
	gcc -c hello.c -o hello.o

1.o:1.c wr.h
	gcc -c 1.c -o 1.o

clean:
	rm -rf *.o helloworld
	
	
