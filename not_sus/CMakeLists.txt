cmake_minimum_required(VERSION 3.22)
project(uwu_mode)

set(CMAKE_CXX_STANDARD 20)

set(GCC_FLAGS "-static")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${GCC_FLAGS}")

add_executable(${PROJECT_NAME} main.cpp src/uwu_keyboard_hook.cpp headers/uwu_keyboard_hook.h src/input_to_uwu_translator.cpp headers/input_to_uwu_translator.h)
