cmake_minimum_required(VERSION 3.5)
project(RISCV_parallel)

set(CMAKE_CXX_STANDARD 14)

add_executable(code main.cpp RISCV.hpp operator.hpp)
