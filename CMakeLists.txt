cmake_minimum_required (VERSION 3.16.3)
project(test2 CXX)


add_subdirectory(dabnn/)
add_executable(test test.cpp)
target_link_libraries(test dabnn)

include_directories(dabnn/)

