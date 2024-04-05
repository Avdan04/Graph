cmake_minimum_required(VERSION 3.27)
project(Graph)

set(CMAKE_CXX_STANDARD 23)

# Указываем исходные файлы вашей библиотеки
set(SOURCES
    graph.hpp
)

# Создаем статическую библиотеку
add_library(Graph STATIC ${SOURCES})


