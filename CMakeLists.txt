cmake_minimum_required(VERSION 3.8)
project(dingC_1)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c blink.h)
add_executable(dingC_1 ${SOURCE_FILES})