Dynamic: matrix_dynamic.o main_dynamic.o
	g++ matrix_dynamic.o main_dynamic.o -o Dynamic

matrix_dynamic.o: matrix_dynamic.c matrix_dynamic.h
	g++ -c matrix_dynamic.c 

main_dynamic.o: main_dynamic.cpp
	g++ -c main_dynamic.cpp

clean:
	rm *.o Dynamic
