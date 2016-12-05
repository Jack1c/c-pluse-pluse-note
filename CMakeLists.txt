cmake_minimum_required(VERSION 3.6)
project(lean1)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp 类型转换.cpp)
add_executable(lean1 ${SOURCE_FILES})