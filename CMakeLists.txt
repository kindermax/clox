cmake_minimum_required(VERSION 3.26)
project(clox C)

set(CMAKE_C_STANDARD 17)
set(SOURCE_FILES src/main.c)

add_executable("${PROJECT_NAME}" ${SOURCE_FILES})
