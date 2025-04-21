cmake_minimum_required(VERSION 3.10.0)
project(ice_breaker VERSION 0.1.0 LANGUAGES C CXX)

add_executable(ice_breaker main.cpp)

include(CTest)
enable_testing()

