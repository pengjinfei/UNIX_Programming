cmake_minimum_required(VERSION 3.5.2)
project(apue_3e)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_subdirectory(lib)
add_subdirectory(filedir bin)


