cmake_minimum_required(VERSION 3.26)
project(helu)

set(CMAKE_CXX_STANDARD 14)

include_directories(lib/count)

add_executable(helu
        lib/count/count.cpp
        lib/count/count.h
        main.cpp)
