cmake_minimum_required(VERSION 3.19)
project(snake C)

set(CMAKE_C_STANDARD 99)

add_executable(snake main.c game.c interface.c stats.c)