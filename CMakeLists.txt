cmake_minimum_required(VERSION 3.10) 

project(Guthi) 
set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_subdirectory("./Platform")

set(CAMKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/bin)