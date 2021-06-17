cmake_minimum_required(VERSION 3.1 FATAL_ERROR)

project(elf-parser VERSION 1.0.0 LANGUAGES C CXX)

add_library(elf-parser INTERFACE)
target_include_directories(elf-parser INTERFACE src/) 
