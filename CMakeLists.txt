cmake_minimum_required(VERSION 3.0)

project(test)
enable_language(Fortran)

add_subdirectory(liba)
add_subdirectory(libb)

add_executable(main main.f90)
target_link_libraries(main a b)
