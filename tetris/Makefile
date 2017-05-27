build: main.o drawer.o
	g++ -o tetris main.o drawer.o -lSDL2 -lm

main.o: main.cpp
	g++ -c main.cpp

world.o: drawer.cpp drawer.h
	g++ -c drawer.cpp -lSDL2 -lm

