cmake_minimum_required(VERSION 3.16)

project(Chapter09)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch09_Sample01_AnimationPlayer "Chapter 09")

target_link_libraries(Ch09_Sample01_AnimationPlayer PRIVATE SharedUtils assimp)