cmake_minimum_required(VERSION 3.0)
project(HelloWorld)

set(CMAKE_CXX_STANDARD 11)

# Either of the two below lines will make make work
set(CMAKE_CXX_COMPILER g++)
#set(CMAKE_CXX_STANDARD_LIBRARIES "-lstdc++")

add_executable(hello_world src/hello_world.cpp)
