cmake_minimum_required(VERSION 3.16)

project(Chapter11)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch11_Sample06_FinalDemo "Chapter 11")

target_link_libraries(Ch11_Sample06_FinalDemo PRIVATE SharedUtils assimp meshoptimizer)
