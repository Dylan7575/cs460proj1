cmake_minimum_required(VERSION 3.4)
project(project1cs460)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.c)
add_executable(project1cs460 ${SOURCE_FILES})