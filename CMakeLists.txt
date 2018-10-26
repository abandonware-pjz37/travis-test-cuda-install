cmake_minimum_required(VERSION 3.2)
project(foo)

enable_language(CUDA)
include_directories(${CMAKE_CUDA_TOOLKIT_INCLUDE_DIRECTORIES})

add_executable(foo foo.cpp)

enable_testing()
add_test(NAME foo COMMAND foo)
