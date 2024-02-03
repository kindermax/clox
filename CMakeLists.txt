cmake_minimum_required(VERSION 3.26)
project(clox C)

set(CMAKE_C_STANDARD 17)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

set(SOURCE_FILES
    src/main.c
    src/common.h
    src/chunk.h
    src/chunk.c
    src/memory.h
    src/memory.c
    src/debug.h
    src/debug.c
    src/value.h
    src/value.c
    src/vm.h
    src/vm.c
    src/compiler.h
    src/compiler.c
    src/scanner.h
    src/scanner.c
)

add_executable("${PROJECT_NAME}" ${SOURCE_FILES})
