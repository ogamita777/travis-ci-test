cmake_minimum_required(VERSION 2.8.7)

enable_language(CXX)
set(CMAKE_CXX_FLAGS "-Wall -Wextra")

project(travis-ci-test)

add_subdirectory(src)