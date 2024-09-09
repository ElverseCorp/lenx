cmake_minimum_required(VERSION 3.10)
project(LenX)


include_directories(include)
file(GLOB_RECURSE LENX_SRC "src/*.c")
add_executable(lenx ${LENX_SRC})