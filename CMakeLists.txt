cmake_minimum_required(VERSION 3.10)

project(irc-cpp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Collect all .cpp files in src/
file(GLOB SOURCES "src/*.cpp")

# Build executable
add_executable(irc-cpp ${SOURCES})
