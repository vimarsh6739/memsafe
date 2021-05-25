# CMakeLists.txt to compile all cpp programs into their own executables
# Author- Vimarsh Sathia

cmake_minimum_required(VERSION 3.8.0)
project(memsafe VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add code subdirectories
add_subdirectory(list)
add_subdirectory(tree)

