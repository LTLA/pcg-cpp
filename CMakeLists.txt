cmake_minimum_required(VERSION 3.14)

project(pcg32
    VERSION 1.0.0
    DESCRIPTION "PCG Random Number Generation, C++ Edition"
    LANGUAGES CXX)

add_library(pcg32 INTERFACE)

target_include_directories(pcg32 INTERFACE include/)
