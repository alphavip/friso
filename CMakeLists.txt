cmake_minimum_required(VERSION 3.16)
project(myfriso C)

include_directories(${PROJECT_SOURCE_DIR}/src)

#target_link_directories(${PROJECT_SOURCE_DIR}/src)

set(${CMAKE_C_FLAGS_DEBUG} "$ENV{CFLAGS} -fPIC -g -Wal")

add_subdirectory(src)
add_subdirectory(test)

