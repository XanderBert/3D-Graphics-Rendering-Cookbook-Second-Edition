cmake_minimum_required(VERSION 3.16)

project(Chapter10)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch10_Sample02_ShadowMapping "Chapter 10")

target_link_libraries(Ch10_Sample02_ShadowMapping PRIVATE SharedUtils assimp meshoptimizer)
