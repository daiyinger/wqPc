funcApp:testMain.o func1.o func2.o 
	gcc -o funcApp testMain.o func1.o func2.o
testMain.o:testMain.c func1.h 
	gcc  testMain.c -c
func1.o:func1.h func1.c
	gcc func1.c -c
func2.o:func2.h func2.c
	gcc func2.c -c
clean:
	rm funcApp testMain.o func1.o func2.o
