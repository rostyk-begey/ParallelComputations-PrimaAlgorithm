cmake_minimum_required(VERSION 3.17)
project(ParallelComputations_PrimasAlgorithm)

set(CMAKE_CXX_STANDARD 20)
SET(CMAKE_CXX_FLAGS -pthread)

add_executable(ParallelComputations_PrimasAlgorithm main.cpp Matrix.cpp Matrix.h ConsoleApp.cpp ConsoleApp.h PrimaAlgorithm.h)