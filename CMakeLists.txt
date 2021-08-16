cmake_minimum_required(VERSION 3.5)
project(lua_tinker)

set(CMAKE_CXX_STANDARD 11)

add_library(lua_tinker STATIC
  lua_tinker.cpp
)
