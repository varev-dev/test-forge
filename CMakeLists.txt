cmake_minimum_required(VERSION 3.15)
project(test_forge)

# Integration with Conan 2.0
set(CMAKE_TOOLCHAIN_FILE ${CMAKE_BINARY_DIR}/conan_toolchain.cmake)
set(CMAKE_PREFIX_PATH ${CMAKE_BINARY_DIR})

# C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Packages
find_package(Qt6 REQUIRED COMPONENTS Core Widgets)
find_package(GTest REQUIRED)

add_subdirectory(src)