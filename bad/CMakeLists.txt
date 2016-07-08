project(foo) # BAD CODE! You should check version first!
cmake_minimum_required(VERSION 3.0)

message("Using CMake version ${CMAKE_VERSION}")
