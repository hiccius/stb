cmake_minimum_required(VERSION 3.0)

project(STB)

add_library(stb_image INTERFACE)

target_include_directories(stb_image INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
