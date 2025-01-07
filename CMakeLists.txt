cmake_minimum_required(VERSION 3.20)
project(problemsolving)

set(CMAKE_CXX_STANDARD 20)

add_compile_definitions(_SHIFTPSH)

add_executable(problemsolving main.cpp)

include_directories(.)