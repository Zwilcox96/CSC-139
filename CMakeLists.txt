cmake_minimum_required(VERSION 3.7)
project(CSC-128)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES consumer.c producer.c)
add_executable(producer producer.c)
add_executable(consumer consumer.c)