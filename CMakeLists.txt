cmake_minimum_required(VERSION 3.0)
project(kidshell)

set(CMAKE_CXX_STANDARD 14)

add_executable(kidshell kidshell.cpp Environment.cpp Environment.h)