cmake_minimum_required(VERSION 3.16)
project(Maximum_Flow_Solver)

include_directories(include)
include_directories(src)

add_executable(app
    src/main.cpp
)