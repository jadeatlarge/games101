cmake_minimum_required(VERSION 2.8.11)
project(Transformation)

# sudo dnf install eigen3-devel
find_package(Eigen3 REQUIRED)
include_directories(EIGEN3_INCLUDE_DIR)

add_executable(Transformation main.cpp)