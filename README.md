
# ASTEROIDS

This is a recreation of the classic asteroids video game. Implemented in the C
programming language, using SDL 2 library to display graphics on the screen.

To compile you need to have SDL 2 installed on your system and the header files
available to you operating systems PATH environment variable

## WebAssembly

To compile for web assembly, run the following command, assuming you have emscripten installed

    emcc \
        -o app.html src/*.c \
        -Wall -g -lm \
        -s USE_SDL=2

A local webserver will be required to load the compiled package

## Controls
* left arrow to rotate left
* right arrow to rotate right
* up arrow to apply thrust in the direction you are pointing
* space to shoot a bullet
* ESC to exit game

## Images
![animation](https://i.imgur.com/sV164D6.gif)

![game play](http://i.imgur.com/vg8nlAO.png)

