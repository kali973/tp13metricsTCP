cmake_minimum_required(VERSION 3.23)
project(tp13metricsTCP)

set(CMAKE_CXX_STANDARD 14)

add_executable(tp13metricsTCP main.c measure_tcp.c measure_tcp.h)
