all:
	make build
	make run
	make clean

build: main.cpp vec2.cpp
	g++ main.cpp vec2.cpp -o vec2

clean:
	find . -type f -name '*.o' -delete
	find . -type f -name '*.a' -delete

run:
	./vec2
