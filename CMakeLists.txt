cmake_minimum_required(VERSION 2.8)

project(test)
file(GLOB SRC src/*.c* src/*.h*)
add_executable(test ${SRC})
