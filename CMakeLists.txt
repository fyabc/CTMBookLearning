cmake_minimum_required(VERSION 2.8)

# set project.
# also create two variables:
# CTMBookLearning_SOURCE_DIR = .
# CTMBookLearning_BINARY_DIR = ./build
# PROJECT_SOURCE_DIR = .
# PROJECT_BINARY_DIR = ./build
project(CTMBookLearning CXX)

# set compiler.
set(CMAKE_C_COMPILER gcc)
set(CMAKE_CXX_COMPILER g++)

# set compiler arguments.
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -g -O2")

# set directories of header files.
# then these header files can be found.
include_directories(${CTMBookLearning_SOURCE_DIR}/include)
