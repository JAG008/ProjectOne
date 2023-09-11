cmake_minimum_required(VERSION 3.24)
project(ProjectOne)

set(CMAKE_CXX_STANDARD 17)

add_library(ProjectOne kvs.cpp main.cpp)
