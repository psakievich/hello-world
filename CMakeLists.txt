cmake_minimum_required(VERSION 3.12.0...3.21.0)
project(hello_world VERSION 0.1.0 LANGUAGES CXX)
add_executable(helloX main.cpp)
target_compile_features(helloX PUBLIC cxx_std_17)
