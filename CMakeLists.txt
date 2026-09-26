cmake_minimum_required(VERSION 3.20)

project(Memory-Allocation)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(my_project
    memory.cpp
)
#cmake -S . -B build
#cmake --build build