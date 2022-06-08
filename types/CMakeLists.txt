cmake_minimum_required(VERSION 3.16)
project(types)

set(CMAKE_CXX_STANDARD 17)
include(ExternalProject)
enable_testing()


add_executable(demo demo.cpp)