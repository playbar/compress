cmake_minimum_required(VERSION 3.4.1)
project(compress LANGUAGES CXX C)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -fexceptions")

add_subdirectory(zlib)



