cmake_minimum_required(VERSION 3.12)
project(test C)

set(CMAKE_C_STANDARD 99)

add_executable(test main.c test1.c test1.h)