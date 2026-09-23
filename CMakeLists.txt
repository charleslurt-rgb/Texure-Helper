cmake_minimum_required(VERSION 3.21)

project(ui_textures)

set(CMAKE_CXX_STANDARD 20)

add_library(${PROJECT_NAME} SHARED
    src/main.cpp
)
