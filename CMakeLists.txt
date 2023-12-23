# cmake ..  -G "MinGW Makefiles"
# cmake --build .
cmake_minimum_required(VERSION 3.22)

project(
      MyProjectNameGCC 
	  VERSION 1.0.0 
	  DESCRIPTION "Build with GCC MinGW"
	  LANGUAGES C CXX)

add_executable(MyProjectNameGCC main.cpp)
 