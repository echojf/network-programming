cmake_minimum_required(VERSION 3.15)
project(unix_network_programming C)

set(CMAKE_C_STANDARD 99)

aux_source_directory(. DIRSRCS)

include_directories(./ ./chapter1)

add_subdirectory(chapter1)

add_executable(unix_network_programming main.c)