.cpp:
	g++ -Wno-deprecated -DUNICODE -I/usr/include/SDL2 -lSDL2 -pthread -std=c++17 $< -o $@.out `sdl2-config --cflags --libs`

clean:
	rm *.out

