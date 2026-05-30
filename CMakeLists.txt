cmake_minimum_required(VERSION 3.10)
project(Lab04)

option(BUILD_EXAMPLES "Build examples" ON)

if(BUILD_EXAMPLES)
    add_executable(example1 main.cpp)
else()
    add_executable(main main.cpp)
endif()
