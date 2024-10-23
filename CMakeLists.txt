cmake_minimum_required(VERSION 3.29)
project(NocionesClaveLibEstatica)

set(CMAKE_CXX_STANDARD 20)

add_library(NocionesClaveLibEstatica STATIC
        src/matematicas.cpp)
