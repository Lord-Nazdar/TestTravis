cmake_minimum_required(VERSION 2.8)
project(TestTravis)

file(GLOB_RECURSE sources src/*.cpp src/*.h)

add_executable(testTravis ${sources})
