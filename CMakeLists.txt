cmake_minimum_required(VERSION 3.10)
project(Sample1Project)

# C++17を指定
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(sample1 sample1.cpp)