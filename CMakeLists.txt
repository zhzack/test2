cmake_minimum_required(VERSION 3.15)
project(test2 C)

set(CMAKE_C_STANDARD 99)

add_executable(test2 main.c num.c num.h)