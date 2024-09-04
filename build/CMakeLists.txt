cmake_minimum_required(VERSION 3.10)

project(Compiler)

add_link_options(-fsanitize=address)

add_compile_options(-Wall -Wextra -g -std=c++20 -fsanitize=address)

add_executable(Compiler ../main.cpp)
