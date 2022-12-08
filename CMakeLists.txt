cmake_minimum_required(VERSION 3.24)
project(UdemyCPP)

set(CMAKE_CXX_STANDARD 17)

add_executable(UdemyCPP main.cpp aula22.cpp aula23.cpp aula24.cpp BubbleSort.cpp aula26.cpp)
add_executable(UdemyCPP_aula22 aula22.cpp)
add_executable(UdemyCPP_aula23 aula23.cpp)
add_executable(UdemyCPP_aula24 aula24.cpp)
add_executable(UdemyCPP_aula26 aula26.cpp)

add_executable(UdemyCPP_BubbleSort BubbleSort.cpp)