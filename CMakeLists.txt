cmake_minimum_required(VERSION 3.20)

project(
  myrender
  LANGUAGES CXX
)

enable_testing()
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_subdirectory(core)

