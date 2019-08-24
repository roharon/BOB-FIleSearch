cmake_minimum_required(VERSION 3.14)
project(FileSearch)

set(CMAKE_CXX_STANDARD 17)

link_directories(${CMAKE_CURRENT_SOURCE_DIR}/cppcore/Build/LinuxRelease)
add_executable(FileSearch main.cpp)
target_link_libraries(FileSearch cppcore)