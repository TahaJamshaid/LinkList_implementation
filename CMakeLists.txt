# cmake_minimum_required(VERSION <specify CMake version here>)
project(Linked_List)

cmake_minimum_required(VERSION 3.3)
project(test_build)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(BUILD_1 main)
set(SOURCE_FILES_1 main.cpp)
add_executable(${BUILD_1} ${SOURCE_FILES_1})

set(BUILD_2 main_2)
set(SOURCE_FILES_2 main2.cpp)
add_executable(${BUILD_2} ${SOURCE_FILES_2})