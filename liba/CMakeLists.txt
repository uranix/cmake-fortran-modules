cmake_minimum_required(VERSION 3.0)

add_library(a
    first.f90
    second.f90
)

target_include_directories(a PUBLIC ${CMAKE_CURRENT_BINARY_DIR})
