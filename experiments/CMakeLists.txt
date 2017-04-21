# Minimum CMake required
cmake_minimum_required(VERSION 3.5)

# Project name
project(experiment)

# Source files
set(SOURCE_FILES getCharPutChar.c)

# executable file name and source to compile
add_executable(getcharputchar ${SOURCE_FILES})
