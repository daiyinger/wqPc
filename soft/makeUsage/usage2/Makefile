objects = testMain.o func1.o func2.o
funcApp:$(objects)
	gcc -o funcApp $(objects)
testMain.o:testMain.c func1.h 
	gcc  testMain.c -c
func1.o:func1.h func1.c
	gcc func1.c -c
func2.o:func2.h func2.c
	gcc func2.c -c
clean:
	rm funcApp $(objects)
