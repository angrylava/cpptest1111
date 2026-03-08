cmake_minimum_required(VERSION 3.29)
project(cpptest1111
        VERSION 1.0
        DESCRIPTION "A simple C++ project"
        HOMEPAGE_URL "https://github.com/angrylava/cpptest1111.git"
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)


set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)
set(Map1_Dir ${CMAKE_SOURCE_DIR}/src/map1)
set(Map2_Dir ${CMAKE_SOURCE_DIR}/src/map2)

add_subdirectory(src)
