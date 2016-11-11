cmake_minimum_required (VERSION 3.0)

project (nil-clang)

add_executable( foo
foo.c)

INSTALL( TARGETS foo DESTINATION "bin")
