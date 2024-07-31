cmake_minimum_required(VERSION 3.29)
project(whereami)

add_library(${PROJECT_NAME} STATIC src/whereami.c)

target_include_directories(${PROJECT_NAME} PUBLIC src)
