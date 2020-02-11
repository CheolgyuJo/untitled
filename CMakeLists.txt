cmake_minimum_required(VERSION 3.14)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp attractclass.cpp attractclass.h)
add_executable(Demo demo.cpp attractclass.cpp attractclass.h cmake-build-debug/Concreat.cpp cmake-build-debug/Concreat.h)