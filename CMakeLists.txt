cmake_minimum_required(VERSION 3.1)

project(Modbus VERSION 3.1.4)

#set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/CMake/")
set(CMAKE_AUTOMOC ON)

include_directories(${CMAKE_CURRENT_BINARY_DIR}/src)
include_directories(${CMAKE_CURRENT_BINARY_DIR})

add_subdirectory(src)
add_subdirectory(tests)
