cmake_minimum_required(VERSION 3.30)
project(AtCoder)

set(CMAKE_CXX_STANDARD 26)

file(GLOB SOURCES
        "main.cpp"
)

add_compile_options(
        -O2 -Wno-unused-result -DONLINEJUDGE
)

# Add files here to execute
add_executable(AtCoder ${SOURCES})
