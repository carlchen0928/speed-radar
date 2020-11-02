cmake_minimum_required(VERSION 3.7)

project(speed_radar)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")

include_directories(include)

add_subdirectory(src "src")
add_subdirectory(examples "examples")
