cmake_minimum_required(VERSION 3.10)

project(Kapengi)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)

# Include directories
include_directories(${CMAKE_SOURCE_DIR}/include)

# Add source directories
add_subdirectory(src)

# Define a default target
add_executable(Kapengi main.cpp)
target_link_libraries(Kapengi ${SOME_LIBRARIES})
