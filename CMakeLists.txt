cmake_minimum_required(VERSION 3.24)
project(window_racer)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(deps/spdlog-1.15.0)

add_executable(window_racer 
    src/event.cpp
    src/window_racer.cpp
)
target_include_directories(window_racer PRIVATE deps/Xoshiro)
target_link_libraries(window_racer PRIVATE spdlog::spdlog)
