cmake_minimum_required(VERSION 3.10)
project(cpp_webserve)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin) 
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/lib)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/lib)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")
include_directories(${CMAKE_SOURCE_DIR}/include)
# add_subdirectory(src ${CMAKE_SOURCE_DIR}/bin)
add_subdirectory(src)






