cmake_minimum_required(VERSION 2.8)
project(canny_edge.cpp)

find_package( OpenCV REQUIRED )

add_executable( canny_edge canny_edge.cpp )
target_link_libraries( canny_edge ${OpenCV_LIBS} )
