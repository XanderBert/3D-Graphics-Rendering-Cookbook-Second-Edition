cmake_minimum_required(VERSION 3.16)

project(Chapter08)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch08_Sample03_LargeScene "Chapter 08")

target_link_libraries(Ch08_Sample03_LargeScene PRIVATE SharedUtils assimp meshoptimizer)
