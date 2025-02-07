cmake_minimum_required(VERSION 3.30)
project(reproduction_library)

set(CMAKE_CXX_STANDARD 20)

add_executable(reproduction_library main.cpp
        basic/algorithm/util_0.cpp)
