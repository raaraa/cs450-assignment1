cmake_minimum_required(VERSION 3.8)
project(Hw1)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES sh.c t.sh)
add_executable(Hw1 ${SOURCE_FILES}  sh.c t.sh)