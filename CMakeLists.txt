cmake_minimum_required(VERSION 3.16.3)

project(skipper VERSION 1.0.0 LANGUAGES CXX)

add_subdirectory(src skippercxx)
add_subdirectory(test skippercxx/test)
