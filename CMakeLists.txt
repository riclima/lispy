cmake_minimum_required(VERSION 3.13)
project(lispy C)

set(CMAKE_C_STANDARD 11)

include_directories(src)

add_executable(lispy
        src/main.c)
