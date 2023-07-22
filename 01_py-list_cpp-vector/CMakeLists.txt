cmake_minimum_required(VERSION 2.8.12)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
project(example)

add_subdirectory(pybind11)
pybind11_add_module(example example.cpp)
