cmake_minimum_required(VERSION 3.16)

project(Chapter01)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch01_Sample02_GLFW "Chapter 01")

target_link_libraries(Ch01_Sample02_GLFW SharedUtils)
