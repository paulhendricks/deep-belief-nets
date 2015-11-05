cmake_minimum_required(VERSION 3.3)
project(deep_belief_nets)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(deep_belief_nets ${SOURCE_FILES})