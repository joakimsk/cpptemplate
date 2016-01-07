cmake_minimum_required( VERSION 2.4 )
project( cpp_program )

# A minimal CMAKE-file to follow the template.

set( CMAKE_CXX_FLAGS "-std=c++11" )

set( SOURCES src/main.cpp )

add_executable( cpp_program ${SOURCES} )

target_link_libraries( cpp_program )