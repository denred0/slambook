cmake_minimum_required( VERSION 2.8 )
project( eigenMatrix )
add_executable( eigenMatrix eigenMatrix.cpp )
include_directories( "/usr/include/eigen3" )
