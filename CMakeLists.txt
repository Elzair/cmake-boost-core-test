cmake_minimum_required(VERSION 3.3)

project(test_core)

add_subdirectory(libs)

add_executable(test_core test.cpp)
target_link_libraries(test_core boost::config boost::assert boost::core)
