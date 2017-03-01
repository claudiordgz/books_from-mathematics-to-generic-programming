cmake_minimum_required(VERSION 3.1.0 FATAL_ERROR)
project(from-math-to-generic-programming)

set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -Wall")
set(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -Wall")

add_executable(02-first-algorithm 02-the-first-algorithm.cpp)

set(CMAKE_CXX_STANDARD 14)
