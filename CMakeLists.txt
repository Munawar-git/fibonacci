cmake_minimum_required(VERSION 3.10)
project(fibonacci)

# Set the C standard
set(CMAKE_C_STANDARD 99)

# Add the executable
add_executable(fibonacci src/main.c src/fibonacci.c)

