cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(project VERSION 1.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# add the executable
add_executable(project range_for_loop.cc) 