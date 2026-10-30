cmake_minimum_required (VERSION 3.14)

project (booz_xform C Fortran)

add_executable (xbooz_xform)
add_dependencies (xbooz_xform pull_booz_xform)

target_link_libraries (xbooz_xform PUBLIC stell)

add_subdirectory (Sources)

install (TARGETS xbooz_xform)
