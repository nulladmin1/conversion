cmake_minimum_required(VERSION 3.20)

project(conversion)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(src)

install(TARGETS conversion DESTINATION bin)
