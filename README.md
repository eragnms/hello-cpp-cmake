# hello-cpp-cmake

This is a short hello world program that will let you compile a c++
program in Windows, using CMake.

## HowTo

Install a C++ compiler: By default, Windows doesn't come with a C++
compiler. You have a few options:


    MinGW: MinGW is a port of the GNU Compiler Collection (GCC) for
    Windows. You can download the MinGW-w64 distribution, which
    provides a 64-bit compiler. Install the variant MSYS2:
    [MSYS2](https://www.msys2.org/)

    In MSYS2 MINGW64 do:

       pacman -Syu pacman -S mingw-w64-x86_64-toolchain make cmake

    Check that we can run:

    	  gcc, g++, cmake and make in MSYS2


Open a command prompt or terminal window clone the hello_world project
and navigate to the root directory of the project.

Then do:

     mkdir build cd build cmake ..  make

Now test the outcome:

    ./hello_world.exe