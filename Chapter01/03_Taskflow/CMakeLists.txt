cmake_minimum_required(VERSION 3.16)

project(Chapter02)

include(../../CMake/CommonMacros.cmake)

SETUP_APP(Ch01_Sample03_TaskFlow "Chapter 01")

target_link_libraries(Ch01_Sample03_TaskFlow SharedUtils)
