cmake_minimum_required(VERSION 3.22)
project(1_lab)

set(CMAKE_CXX_STANDARD 14)

include_directories("12(proga)")
include_directories("12(proga)/cmake-build-debug")
include_directories("laba1.1(proga)")
include_directories("laba1.1(proga)/cmake-build-debug")
include_directories("laba1.4(proga)")
include_directories("laba1.9(proga)")
include_directories("laba1.9(proga)/cmake-build-debug")

add_executable(1_lab
        "12(proga)/cmake-build-debug/func.cpp"
        "12(proga)/cmake-build-debug/func.h"
        "12(proga)/func.cpp"
        "12(proga)/func.h"
        "12(proga)/main.cpp"
        "laba1.1(proga)/cmake-build-debug/fun.h"
        "laba1.1(proga)/fun.cpp"
        "laba1.1(proga)/fun.h"
        "laba1.1(proga)/main.cpp"
        "laba1.4(proga)/fun.cpp"
        "laba1.4(proga)/fun.h"
        "laba1.4(proga)/main.cpp"
        "laba1.9(proga)/cmake-build-debug/fun.h"
        "laba1.9(proga)/fun.cpp"
        "laba1.9(proga)/fun.h"
        "laba1.9(proga)/main.cpp")
