cmake_minimum_required(VERSION 3.27)
project(Lab5)

set(CMAKE_CXX_STANDARD 17)

add_executable(Lab5
        src/main.cpp
        src/task.h
        src/task1.cpp
        src/task2.cpp
        src/task3.cpp
        src/task4.cpp
)

add_executable(Lab5_example
        src_example/Chiselki5.cpp
        src_example/Methods.h
)
