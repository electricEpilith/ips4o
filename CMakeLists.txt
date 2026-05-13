cmake_minimum_required(VERSION 3.22...4.2)

project(ips4o
    LANGUAGES CXX
)

#copied from ips4o/ips4o
add_library(ips4o INTERFACE)
target_include_directories(ips4o INTERFACE include/)