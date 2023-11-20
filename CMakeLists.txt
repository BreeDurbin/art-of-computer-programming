cmake_minimum_required(VERSION 3.14)

project(leetcode-solutions LANGUAGES CXX)
set (CMAKE_CXX_STANDARD 20)

add_subdirectory(src/solutions)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ./build)