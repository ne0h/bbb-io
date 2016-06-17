cmake_minimum_required (VERSION 2.8)
project (BeagleBoneBlackIO)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

include_directories(..)
add_executable(i2c_mpu6050
	../i2c.c
	i2c_mpu6050.cpp
)

