cmake_minimum_required(VERSION 3.16)

project(Chapter04)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch04_Sample06_DemoApp "Chapter 04")

target_link_libraries(Ch04_Sample06_DemoApp PRIVATE SharedUtils assimp)
