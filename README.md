==CMake Tutorial==
This tutorial can be found on https://cmake.org/cmake-tutorial/ where also the link to a gitlab repository with the code is given

==Build the project==
Go into the root of this project and type 'cmake .'. Finally 'make install' which will try to copy the exectuable to /usr/local/bin.
Type 'make DESTDIR=/path/to/somewhere install' to install somewhere else.

==Tests==
Run 'ctest' in project root to run the tests defined in CMakeLists.txt.
