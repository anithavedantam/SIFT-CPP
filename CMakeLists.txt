cmake_minimum_required(VERSION 3.10)
project(SIFTKeypointMatcher)

find_package(OpenCV REQUIRED)

add_executable(SIFTKeypointMatcher main.cpp)
target_link_libraries(SIFTKeypointMatcher ${OpenCV_LIBS})

