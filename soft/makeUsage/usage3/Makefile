objects = testMain.o func1.o func2.o
CC = gcc
funcApp:$(objects)
	$(CC) -o funcApp $(objects)
testMain.o:testMain.c func1.h 
	$(CC)  testMain.c -c
func1.o:func1.h func1.c
	$(CC) func1.c -c
func2.o:func2.h func2.c
	$(CC) func2.c -c
clean:
	rm funcApp $(objects)
