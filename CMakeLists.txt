cmake_minimum_required(VERSION 3.15)
project(console_menu)

set(CMAKE_CXX_STANDARD 20)

add_library(console_menu menu.cpp menu.h resources.h menu_element.cpp menu_element.h)