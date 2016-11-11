cmake_minimum_required (VERSION 3.0)

project (nil-cmake)

add_executable( foo
foo.c)

message( STATUS "CMAKE_C_COMPILER_ID is ${CMAKE_C_COMPILER_ID}")
message( STATUS "CMAKE_C_COMPILER is ${CMAKE_C_COMPILER}")

INSTALL( TARGETS foo DESTINATION "bin")
