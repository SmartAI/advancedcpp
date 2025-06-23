cmake_minimum_required(VERSION 3.28)
project(cpp LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED true)
set(CMAKE_VERBOSE_MAKEFILE ON)

add_subdirectory(crtp)
add_subdirectory(modules)


