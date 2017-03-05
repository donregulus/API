cmake_minimum_required(VERSION 3.5.1)
include_directories (${CMAKE_SOURCE_DIR}/include/)
add_library(coord3d_UnitTest ${CMAKE_CURRENT_SOURCE_DIR}/coord_UnitTest.cpp)
target_link_libraries(coord3d_UnitTest LINK_PUBLIC geometry)
