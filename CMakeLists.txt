cmake_minimum_required(VERSION 3.29)
project(complex)

set(CMAKE_CXX_STANDARD 26)

add_executable(complex main.cpp
        Complex.cpp
        Complex.h)
