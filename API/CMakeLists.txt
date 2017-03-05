cmake_minimum_required(VERSION 3.5.1)
add_library(position ${CMAKE_CURRENT_SOURCE_DIR}/src/position/coord.cpp) #"position/coord3d.cpp" need to be change by a regex
target_include_directories (position PUBLIC ${CMAKE_CURRENT_BIN_DIR})
add_subdirectory(unitest/)


#add_subdirectory(include/test)
