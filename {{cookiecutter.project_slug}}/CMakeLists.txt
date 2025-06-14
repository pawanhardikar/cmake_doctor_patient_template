cmake_minimum_required(VERSION 3.15)
project({{cookiecutter.project_slug}})

set(CMAKE_CXX_STANDARD 17)
include_directories(include)

file(GLOB SOURCES "src/*.cpp")
add_executable({{cookiecutter.project_slug}} ${SOURCES})