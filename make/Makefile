all: hello

hello: name.o
	g++ name.o -o hello
	./hello
name.o: name.cpp
	g++ -c name.cpp	
	
clean:
	rm -rf *o hello
	
