cmake_minimum_required(VERSION 3.10)
project(Graph)

# Укажите стандарт C++.
set(CMAKE_CXX_STANDARD 17)

# Создайте библиотеку вместо исполняемого файла.
# Используйте 'SHARED' для динамической библиотеки или 'STATIC' для статической.
add_library(Graph STATIC graph.cpp graph.h)


