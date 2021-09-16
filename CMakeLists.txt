cmake_minimum_required(VERSION 3.13 FATAL_ERROR)
project(asio VERSION 1.18.2 LANGUAGES CXX)

add_library(asio INTERFACE)
target_include_directories(asio
        INTERFACE
            ${CMAKE_CURRENT_SOURCE_DIR}/include)