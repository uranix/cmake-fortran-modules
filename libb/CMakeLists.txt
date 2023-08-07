cmake_minimum_required(VERSION 3.0)

add_library(b
    second.f90
    third.f90
)

target_include_directories(b PUBLIC ${CMAKE_CURRENT_BINARY_DIR})
