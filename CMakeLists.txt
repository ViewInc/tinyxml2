cmake_minimum_required(VERSION 3.4.1)

project(tinyxml2)

add_library( # Specifies the name of the library.
        tinyxml2 STATIC
        ./tinyxml2.cpp)

include_directories(${CMAKE_CURRENT_LIST_DIR})