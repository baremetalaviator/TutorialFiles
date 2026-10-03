cmake_minimum_required(VERSION 3.20)
project(Exercises C)

add_executable(hello tests/host/hello.c)
target_compile_options(hello PRIVATE -Wall -Wextra -Wpedantic -Werror)