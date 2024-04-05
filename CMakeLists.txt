cmake_minimum_required(VERSION 3.27)
project(Graph)

set(CMAKE_CXX_STANDARD 23)

# Указываем путь к заголовочным файлам вашего репозитория
include_directories(${CMAKE_CURRENT_SOURCE_DIR})

# Добавляем все исходные файлы в список SOURCES
set(SOURCES
    graph.hpp
)

# Создаем статическую библиотеку
add_library(Graph STATIC ${SOURCES})
