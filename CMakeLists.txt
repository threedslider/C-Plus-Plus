cmake_minimum_required(VERSION 3.17)
project(c_plus)

set(CMAKE_CXX_STANDARD 20)

add_executable(c_plus src/basic/hello.cpp)
add_executable(c_plus_pre src/basic/pre_define.cpp)
add_executable(c_plus_exp src/basic/explain_code_basic.cpp)
add_executable(c_plus_triangle src/basic/triangle.cpp)