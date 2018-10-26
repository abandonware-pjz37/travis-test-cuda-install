cmake_minimum_required(VERSION 3.2)
project(foo)

add_executable(foo foo.cpp)

enable_testing()
add_test(NAME foo COMMAND foo)
