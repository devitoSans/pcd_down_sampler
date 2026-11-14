cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

project(pcd_down_sampler)

find_package(PCL 1.2 REQUIRED)

add_executable (pcd_down_sampler pcd_down_sampler.cpp)
target_link_libraries (pcd_down_sampler ${PCL_LIBRARIES})