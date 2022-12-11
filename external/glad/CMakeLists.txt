cmake_minimum_required(VERSION 3.13 FATAL_ERROR)

set(PROJECTNAME GLAD)

project(${PROJECTNAME})

add_library(${PROJECTNAME} STATIC include/glad/glad.h src/glad.c)

target_include_directories(${PROJECTNAME} PUBLIC include/)