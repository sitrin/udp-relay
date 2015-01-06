cmake_minimum_required(VERSION 2.6)
project(UDP-Tunnel)

set(CMAKE_CXX_FLAGS "-g -Wall -std=c++11")

add_executable(udp-tunnel.exe main.cpp)

