cmake_minimum_required(VERSION 3.12)
project(T1)

set(CMAKE_CXX_STANDARD 17)

file(GLOB T1_SRC
    main.cpp
    "./src/*.h"
    "./src/*.cpp"
)

add_executable(T1 ${T1_SRC})
