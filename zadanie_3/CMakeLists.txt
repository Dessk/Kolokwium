cmake_minimum_required(VERSION 3.8)
project(Kolokwium)
file(GLOB SOURCES "*.cpp")
add_library(myLib SHARED address.h employee.h)

add_executable(myProgram ${SOURCES})
target_link_libraries(myProgram myLib)
