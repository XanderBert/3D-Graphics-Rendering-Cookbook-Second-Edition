cmake_minimum_required(VERSION 3.16)

project(Chapter05)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch05_Sample05_Grid "Chapter 05")

target_link_libraries(Ch05_Sample05_Grid PRIVATE SharedUtils assimp)
