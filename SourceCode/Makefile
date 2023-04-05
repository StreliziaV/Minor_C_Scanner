EXEC_NAME = scanner

all : $(EXEC_NAME)

$(EXEC_NAME) : added.o scanner.cpp
	g++ -o scanner added.o scanner.cpp

added.o : added.cpp
	g++ -c added.cpp

clean:
	rm -rf added.o scanner output.txt
