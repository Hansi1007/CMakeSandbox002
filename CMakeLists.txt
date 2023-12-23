# cmake ..  -G "Visual Studio 17 2022"
# cmake --build .
cmake_minimum_required(VERSION 3.22)

project(
      MyProjectName 
	  VERSION 1.0.0 
	  LANGUAGES C CXX)
set(CMAKE_CXX_STANDARD 20)	  

add_executable(MyProjectName main.cpp)
