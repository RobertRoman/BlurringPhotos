build: main
main: main.c
	mpicc -o main main.c -lm -Wall
run:
	mpirun -np 4 main blur.pnm result.pnm
clean:
	rm -f main
