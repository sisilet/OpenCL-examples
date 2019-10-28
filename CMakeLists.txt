cmake_minimum_required (VERSION 3.8)
find_package( OpenCL REQUIRED )

link_directories( ${OpenCL_LIBRARY} )
include_directories( BEFORE ${OpenCL_INCLUDE_DIRS} )
add_subdirectory(example00)
add_subdirectory(example01)
add_subdirectory(example02)
add_subdirectory(example03)
#add_subdirectory(example04)
#add_subdirectory(example05)


# https://github.com/Dakkers/OpenCL-examples