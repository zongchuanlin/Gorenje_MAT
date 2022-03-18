cmake_minimum_required(VERSION 3.21)
project(Gorenje_MAT)

set(CMAKE_CXX_STANDARD 11)

add_executable(Gorenje_MAT main.cpp lib/CSerialPort.h main/MAT_main.cpp main/SerialPort.cpp)
