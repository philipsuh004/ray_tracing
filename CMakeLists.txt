cmake_minimum_required(VERSION 3.16)
project(ray_tracing LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(src)

target_include_directories(ray_tracing PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)