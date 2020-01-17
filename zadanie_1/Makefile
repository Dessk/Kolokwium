myProgram: main.o address.o employee.o
		g++ main.o -o myProgram

main.o: main.cpp address.h employee.h
		g++ -I include -c main.cpp

address.o: address.cpp
		g++ -c address.cpp

employee.o: employee.cpp address.h
		g++ -I include -c employee.cpp
