cmake_minimum_required(VERSION 3.8.0)
project(lab_02 VERSION 0.1.0 LANGUAGES C CXX)

# C++ Standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Source
set(SOURCES 
    src/main.cpp
)

add_executable(lab_02 ${SOURCES})

