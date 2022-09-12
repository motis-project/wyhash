cmake_minimum_required(VERSION 3.10)
project(wyhash)

add_library(wyhash INTERFACE)
target_include_directories(wyhash SYSTEM INTERFACE .)
