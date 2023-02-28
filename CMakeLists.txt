cmake_minimum_required(VERSION 3.13)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON) 
#set(CMAKE_VERBOSE_MAKEFILE      ON)


project(main)

file(GLOB_RECURSE sources      src/*.cpp src/*.h)


add_executable(main 
    ${sources}
    "main.cpp"
)
