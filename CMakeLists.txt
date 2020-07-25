cmake_minimum_required(VERSION 3.16)
project(OrderSystem)

set(CMAKE_CXX_STANDARD 14)

add_executable(OrderSystem main.cpp Menu.cpp Menu.h User.cpp User.h)