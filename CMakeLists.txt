
project(thread_pool)
cmake_minimum_required(VERSION 3.2)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS "ON")

add_executable(thread_pool_tests ${CMAKE_CURRENT_SOURCE_DIR}/tests/BS_thread_pool_test.cpp)
target_include_directories(thread_pool_tests PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
