cmake_minimum_required(VERSION 3.0)
project(TestTravis)

file(GLOB_RECURSE sources src/*.cpp src/*.h)

add_executable(testTravis ${sources})
