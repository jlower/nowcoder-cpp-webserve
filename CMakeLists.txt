cmake_minimum_required(VERSION 3.10)
project(cpp_webserve)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")
add_subdirectory(src ${PROJECT_SOURCE_DIR}/bin)

