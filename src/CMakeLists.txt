include_directories(${PROJECT_SOURCE_DIR}/include)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")
aux_source_directory(. SRC_LIST)
add_executable(${CMAKE_PROJECT_NAME} ${SRC_LIST})

