This is a biicode adaptation of the original repository:
[https://github.com/lvandeve/lodepng.git](https://github.com/lvandeve/lodepng.git) through the fork: mhernando/lodepng


No changes needed (only the SDL dependencies of the examples): 
SDL/SDL.h --> miguel/sdl2/include/SDL.h
SDL examples does not work because they rely on the 1.x SDL version. This examples should be upgraded.


It is an amazing code.




ORIGINAL README:

LodePNG
-------

PNG encoder and decoder in C and C++.

Home page: http://lodev.org/lodepng/

Only two files are needed to allow your program to read and write PNG files: lodepng.cpp and lodepng.h.

The other files in the project are just examples, unit tests, etc...
