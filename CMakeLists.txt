cmake_minimum_required(VERSION 3.0.0)
project(template_cmake VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_subdirectory(src)
add_subdirectory(tests)
add_subdirectory(lib/googletest)
