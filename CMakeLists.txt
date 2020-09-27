cmake_minimum_required(VERSION 3.14)
project(libtest C)

set(CMAKE_C_STANDARD 99)

add_library(libtest SHARED library.c library.h)
