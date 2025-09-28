cmake_minimum_required(VERSION 4.0)
project(FILASEX C)

set(CMAKE_C_STANDARD 23)

add_executable(FILASEX main.c
        backendfila.c
        escopofila.h)
