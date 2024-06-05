cmake_minimum_required(VERSION 3.10)

project(Submodule_Template)

add_subdirectory("lib/logger")

add_executable(${PROJECT_NAME} main.c)
target_link_libraries(${PROJECT_NAME} Logger)