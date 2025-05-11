cmake_minimum_required(VERSION 3.10)
project(kbral)

# add the files .c in exec
add_executable(kbral
    chunk.c
    memory.c
    main.c
    debug.c
    value.h
)

target_include_directories(kbral PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})