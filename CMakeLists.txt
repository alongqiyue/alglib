cmake_minimum_required(VERSION 3.6)
project(alglib)

set(CMAKE_CXX_STANDARD 11)

file(GLOB ALGLIB_SRCS "src/*.cpp")
file(GLOB ALGLIB_HRDS "src/*.h")

add_library(alglib
  ${ALGLIB_SRCS}
  ${ALGLIB_HRDS})