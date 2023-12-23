# cmake ..  -G "MinGW Makefiles"
# cmake --build .
cmake_minimum_required(VERSION 3.22)

project(
      MyProjectNameGCC 
	  VERSION 1.0.0 
	  LANGUAGES C CXX)
set(CMAKE_CXX_STANDARD 20)	  

add_executable(MyProjectNameGCC main.cpp)
