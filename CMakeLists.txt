cmake_minimum_required(VERSION 3.10)

project(CompiledApp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file(GLOB_RECURSE SOURCES "app/*.cpp")

add_executable(CompiledApp ${SOURCES})
