cmake_minimum_required(VERSION 3.23)
project(EX1)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(DEV)

add_executable(EX1
        DEV/main.cpp)
