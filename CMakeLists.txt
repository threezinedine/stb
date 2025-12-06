cmake_minimum_required(VERSION 3.20)
project(stb)

add_library(stb INTERFACE)

target_include_directories(
    ${PROJECT_NAME}
    INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}
)
