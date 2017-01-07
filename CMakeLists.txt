cmake_minimum_required(VERSION 3.1)

project(Toys CXX)

set(Projects_Path projects)

include_directories(libs)

add_subdirectory(projects)
add_subdirectory(tests)
